# FridaLink
A GUI Python application to easily guide and help root your Quest 3/3s on Windows 10 and above

This is a modding tool that involves rooting your device. Use it at your own risk. I take zero responsibility for any damage caused to your headset, your game account, or anything else. Always be respectful to other players and follow the terms of service of the game.

Before you begin, ensure you have the following:

    A Meta Quest 3 or 3S headset. Quest 2 is not compatible with this root exploit

    Developer Mode enabled on your headset.

    A PC running Windows 10 or 11. Any other os is not OFFICIALY supported

    A USB-C cable to connect your headset to your PC for the initial setup. Preferably capable of data transfer
    (OEM charging cable works fine)

This program was vibe-coded with AI (specifically Google's Gemini 2.5 Pro)
# Troubleshooting
## More than one device/emulator when running `adb shell ip addr show wlan0`
Run adb devices, if you see 2 devices, one with a stand and another with an ip address with port 5000, run `adb disconnect x.x.x.x:5000` with `x.x.x.x` being the headsets ip address seen in `adb devices`
