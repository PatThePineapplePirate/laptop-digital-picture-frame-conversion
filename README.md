# Old Laptop to Digital Picture Frame Conversion
Documentation for converting an old laptop into a digital picture frame.

<p align="center"><img alt="Dell Inspiron 6000 laptop model nameplate" src="/images/dell-laptop-model.jpg" height="600" width="auto"><img alt="finished digital frame powered on to desktop" src="/images/digital-frame-front.jpg" height="600" width="auto"></p>

## <a name="purpose"></a>Purpose
I wanted to save dated Dell Inspiron 6000 from becoming E-Waste. This is the process I took several years ago to deconstruct, mat the screen, and install the hardware into a shadowbox frame to give the computer new life as a digital picture frame. 

>Unfortunately the images are a bit lower quality and portrait orientation, but I will supplement them with relevant information as necessary.  


## Table of Contents

  - [Purpose](#purpose)
  - [Hardware](#hardware)
  - [Construction](#construction)
    - [Disassembly](#disassembly)
    - [Mat the Screen](#mat-the-screen)
    - [Mount in the Frame](#mount-in-the-frame)
    - [Interface Decisions](#interface-decisions)
  - [Displaying Pictures](#displaying-pictures)
  - [Lessons Learned](#lessons-learned)
  - [License](#license)

## <a name="hardware"></a>Hardware

I already owned the laptop and the wireless keyboard + dongle, so my only investment to finish the project was for a frame and mat. I made sure that the shadow box frame would fit the width, height, and depth of the laptop parts, and that the mat internal framing dimentions were slightly smaller than the laptop screen so I could cut it to size. These remaining materials cost around $40USD. 

| Item    | Source | Additional information | 
| :-------- | :------- | :------- |
| [Dell Inspiron 6000](https://github.com/PatThePineapplePirate/laptop-digital-picture-frame-conversion/blob/main/docs/dell_esuprt_laptop_esuprt_inspiron_laptop_inspiron-6000_ownermanual_en-us.pdf) | Unused old laptop | Pentium M, 512MB RAM, 15.4" Screen |
| Shadow Box Frame | Craft Store | 12" x 16" |
| Mat Board | Col2Val3 | 12" x 16" but interior cut to fit screen size |
| Wireless Keyboard and Dongle | Amazon, Best Buy, etc | I went with Logitech K400 Plus |

<p align="center"><img alt="Example Shadow Box frame front" src="/images/stock-frame-front.jpeg" height="auto" width="400"><img alt="Example Shadow Box frame back" src="/images/stock-frame-back.jpeg" height="auto" width="400"></p>

## <a name="construction"></a>Construction

### <a name="disassembly"></a>Disassembly
The first step was disassembling the bulky laptop to remove all the housing pieces. The <a href="https://www.ifixit.com/Device/Dell_Inspiron_6000">iFixit guide</a> and <a href="https://www.ifixit.com/Device/Dell_Inspiron_6000">Service Manual</a> were referenced, but disassembly was pretty straightforward. Extra care was taken with screen ribbon cables and wifi antennas. The battery and keyboard were also disposed of with the frame pieces. 

<p align="center"><img alt="ifixit Dell Inspiron 6000 Image" src="/images/ifixit-dell-inspiron-6000.jpg" height="auto" width="auto"><br>
Image source: <a href="https://www.ifixit.com/Device/Dell_Inspiron_6000">iFixit</a></p>

<p align="center"><img alt="layout of disassembled laptop pieces" src="/images/dell-laptop-disassembly.jpg" height="600" width="auto"></p>

> [!NOTE]
> During this step I replaced the thermal paste on the processor by unscrewing the heat pipe/heatsink assembley on the CPU. This was completely unnecessary for the demands of the new photo frame, but I wanted to take the opportunity to explore since I don't frequently take laptops apart.

### <a name="mat-the-screen"></a>Mat the Screen
I purchased a mat board that fit inside the shadow box frame but that had interior dimensions slightly smaller than my leptop screen. Using a utility knife and straight edge, I cut the mat to exactly fit the screen, then secured it and the wifi antennas in place with duct tape. 

I verified that the screen ribbon cables would connect and reach with the laptop hardware mounted behind the screen as if you had opened the laptop 360° like a 2-in-1.

<p align="center"><img alt="screen back mounted to mat" src="/images/digital-frame-screen-mat-back.jpg" height="600" width="auto"><img alt="screen front mounted to cut mat" src="/images/digital-frame-screen-mat-front.jpg" height="600" width="auto"></p>

### <a name="mount-in-the-frame"></a>Mount in the Frame
In this fully overextended screen orientation, the laptop internals were well suited to mounting in the shadow box frame for the purposes of becoming a digital picture frame:  

  - Many critical components were in the bottom middle and corner, and could be accessed by cutting part of the back cover away.
    - The CPU and it's cooling were exposed.
    - The power button board was accessible.
    - A USB port for I/O is just inside the cutaway.
  - The barrel connector for powering the device was now on the bottom, and was exposed by slightly cutting into the bottom of the frame.

<p align="center"><img alt="Hardware insert and back cover cutaway" src="/images/digital-frame-back.jpg" height="600" width="auto"></p>

### <a name="interface-decisions"></a>Interface Decisions

## <a name="displaying-pictures"></a>Displaying Pictures
My goal for displaying the pictures was to make it as simple to set up and maintain as possible. I decided an easy and somewhat software agnostic way was to use either the desktop background or screensaver settings for the slideshow. This is easy to set up in Windows and also worked on the lightweight <a href="https://linuxmint.com/download.php">Linux Mint Xfce</a> installation I put on the laptop. 

Generally speaking for setting as a desktop background, you would want to select the folder with images in it you want to display, hide all desktop icons and task bars, and update power settings to use as little power as possible while never turning the screen off or sleeping. 

As a screensaver you could similarly point to your photo folder, set a short screensaver startup time, but still make sure power settings prevent the computer from sleeping or shutting down. 

<p align="center"><img alt="powered on photo frame" src="/images/digital-frame-front.jpg" height="600" width="auto"></p>

## <a name="lessons-learned"></a>Lessons Learned

## <a name="license"></a>License

GPLv3 or later