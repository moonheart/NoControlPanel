[[EN](README.md)|[CN](README_CN.md)]

# NoControlPanel On Xiaomi 12s Ultra

The Mi 12s series is forced to use the new version of the Control Center. If you want to use the classic control center, you can modify it as follows.

Use MT Manager to find `/system/product/overlay/DevicesOverlay.apk` and copy it to internal storage such as `Documents/DevicesOverlay.apk`, open the `resources.arsc` file through Arsc editor. Find `com.miui.systemui.devices.overlay/integer/integer/force_use_control_panel` and change the value to 0.

Save the apk. If it is MIUI 14/Android 13, you need to sign the apk to be recognized by the system, just use the signature tool that comes with MT Manager.

Finally, it is overwritten to the system through the magisk module.

https://github.com/moonheart/NoControlPanel/releases/download/v14.0.2/Xiaomi12sUltraClasicControlCenter-14.0.2.zip
