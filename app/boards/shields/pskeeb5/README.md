

## FULL BUILD
```
source .venv/bin/activate
west build -s app -d build -b nice_nano_v2 -S zmk-usb-logging -S studio-rpc-usb-uart -p  -- -DSHIELD=pskeeb5_right -DCONFIG_ZMK_STUDIO=y -DCONFIG_ZMK_STUDIO_LOCKING=n
```
