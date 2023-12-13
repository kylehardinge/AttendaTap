# Building code for the device

Following the instructions here - https://esp-rs.github.io/book/installation/index.html - follow the instructions based on your chip.

Right now, I have an Xstensa chip, the esp32-wroom-32. It's a vanilla esp32, no v3 or s or anything.

You could also (probably) use a container provided by Espressif - check here for that: https://esp-rs.github.io/book/installation/using-containers.html

The build directory is AttendaTap/device, and to be able to actually run it, you need espflash installed as well (just run cargo install espflash)
I also had to download the windows driver from here - https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads - to get it to work properly
And as a final note, my chip requires you (infuriatingly) to hold down the IOO button to get it to connect.