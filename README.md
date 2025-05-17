# Device Spoof Module

## Description
This Magisk module allows you to spoof your device information to appear as various phone brands including Infinix, Vivo, Samsung, Realme, and Redmi. By default, it's configured to spoof as a VIVO X200 Pro.

## Features
- Spoofs device manufacturer, brand, model and other device identifiers
- Compatible with Magisk v29000+
- Works on Android 10+ devices
- Easy to customize for different device brands

## Installation
1. Download the module zip file
2. Open Magisk Manager
3. Go to Modules section
4. Click on "Install from storage"
5. Select the downloaded zip file
6. Reboot your device

## Configuration
The module comes pre-configured to spoof your device as a VIVO X200 Pro. If you want to spoof as a different device:

1. After installation, navigate to `/data/adb/modules/device_spoof_module/`
2. Edit the `system.prop` file
3. Uncomment the desired device section (Samsung, Realme, Redmi, or Infinix)
4. Comment out the current active section
5. Reboot your device

## Troubleshooting
If the module doesn't work properly:
- Make sure you're using Magisk v29000 or higher
- Check if the module is enabled in Magisk Manager
- Try disabling and re-enabling the module
- Check the logs in `/data/adb/modules/device_spoof_module/spoof_log.txt`

## Credits
- Author: willygailo01@gmail.com
- Compatible with Android 10+ devices

## Disclaimer
This module is provided as-is with no warranties. Use at your own risk. The author is not responsible for any damage caused by using this module.

## License
This module is free to use and distribute. 
