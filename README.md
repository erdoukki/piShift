<img src="https://raw.githubusercontent.com/tomhartley/piShift/master/images/logo.png" width="350">

piShift makes it super simple to get programming on your Pi Zero - just plug your Pi into your laptop with a micro-USB cable and it appears as a USB Drive. Drag across a .py file, and within seconds the Pi will automatically detect it's been added, and will start running the most recently edited file.

#Installation
1. Install Raspbian (full, not lite) onto an SD card
2. Get internet on your Pi - you can do this with a USB hub + WiFi dongle on the PiZero, or by temporarily putting your SD card into a B+/2/3 .
3. Run the following commands: 
```
git clone git clone https://github.com/tomhartley/piShift.git --branch rewrite
cd piShift
sudo ./install.sh
```

Now attach a micro-USB cable to the USB port marked "USB" on the PiZero, plug into your computer, and you should be good to go!
