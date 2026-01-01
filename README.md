# HDZero BoxPro Firmware mod
This is a QoL modification for the HDZero BoxPro Firmware.

Current list of added features:
- RSSI label and number next to the analog RSSI bar
- Scan analog page just like the original "Scan now" for HDZero. Scans all analog channels and allows you to see which is active

NOTES:
- Use the right side button after analog scanning to go to the next band, and use the roller to select a frequency
- If no active frequencies were detect, scrolling will move to the next page (that is intentional)

## How to install
### Temp install
Do this if you just want to try it out.
1. Go to releases and download the `tryit.zip`
2. Inside should be a `develop.sh` and a `HDZGOGGLE`
3. Move those two files to the root directory of your sd card
4. Plug the sd card into the goggles and then turn it on
5. Removing these two files from your sd card will cause the goggle to go back to the original firmware
### Permanent install
Note you can always go back to the original firmware by downloading it from the offical website and flashing it. You don't need the sd card plugged in for this.
1. Download the `HDZERO_BOXPRO-x.x.x.bin` from releases
2. Put it in the root directory of your sd card
3. Boot it up, and go to the firmware tab and click update BoxPro
4. Follow instructions on screen, don't power off!
