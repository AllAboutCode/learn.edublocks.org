---
id: getting-started-mb
summary: A getting started guide to learn more about getting connected and setup with your BBC micro:bit.
categories: micro:bit
tags: guide, micro:bit, getting started, help
difficulty: 2
status: published
published: 2019-04-19
author: Joshua Lowe
feedback_url: https://github.com/AllAboutCode/learn.edublocks.org/issues

---

# Getting started with the BBC micro:bit

## What is the micro:bit mode?

The micro:bit mode within EduBlocks v3 allows you to code the BBC micro:bit in MicroPython using a drag and drop interface. 

![screenshot](Screenshot_2019-04-18 edublocks.png)

## What is the BBC micro:bit
Duration: 2:00

The BBC micro:bit is a small microcontroller which was originally created to be handed out to 1 million eleven year old children (Year 7's) in the UK. They are now available for public availability and the project is now carried on by the Micro:bit Educational Foundation. The micro:bit consists of:
  - A 5x5 LED matrix display
  - 2 tactile buttons
  - An accelerometer and compass
  - A radio and bluetooth antenna
  - An edge connector for accessories

![screenshot](https://www.kitronik.co.uk/wp/wp-content/uploads/2015/07/Microbit-GIF-870-pix.gif)

## Launching the micro:bit mode
Duration: 3:00

So, you've got your micro:bit and you want to get started with using it with EduBlocks. Let's get into it!

### You will need:
  - A BBC micro:bit
  - An internet connection
  - A computer with a USB port
  - A micro USB cable

### Load up EduBlocks

In a modern browser of your choice (we've found Google Chrome works best), launch the following web address:

positive
: **Web Address**
  [https://app.edublocks.org](https://app.edublocks.org)

### Launch the mode

You’ll need to load up EduBlocks. You can do this by opening a web browser of your choice and typing [https://app.edublocks.org](https://app.edublocks.org) into the search box. Once you've loaded up EduBlocks, you'll be presented with the mode selector. 

![screenshot](https://i.ibb.co/tQ0JcTz/Screenshot-2019-04-14-edublocks.png)

Now, we want to select the micro:bit mode. To do this simply click on the blue select button underneath the micro:bit icon. This will load up the micro:bit mode.

Once you've selected the micro:bit mode, you should see it pop up:

![screenshot](https://i.ibb.co/93PHxFY/Screenshot-2019-04-14-edublocks-2.png)

## Loading up samples
Duration: 4:00

Once inside the micro:bit mode, we have a range of different things we can do. Before you write your own program it's a good idea to load up a sample so you can see how EduBlocks works.

To load up a sample, click the samples button in the blue navbar at the top, this will load up the following dialog box: 

![screenshot](https://camo.githubusercontent.com/bb466f277380e59cbc695a69c55017c7206b767a/68747470733a2f2f626c6f627363646e2e676974626f6f6b2e636f6d2f76302f622f676974626f6f6b2d32383432372e61707073706f742e636f6d2f6f2f6173736574732532462d4c55764a5566454d5767353248482d516f634f2532462d4c55764a625f5639766671476845557a32354c2532462d4c557651447a736269456d7a5478596d5f3646253246696d6167652e706e673f616c743d6d6564696126746f6b656e3d35303539366135662d316237362d346463652d623062642d613138393830366330626635)

Click on the blue open button next to the "Buttons" sample. 
Once you've done this, a few blocks should appear in the workspace.

![screenshot](https://camo.githubusercontent.com/de4569c6f4c494666b86ab758edff88af6c7486f/68747470733a2f2f626c6f627363646e2e676974626f6f6b2e636f6d2f76302f622f676974626f6f6b2d32383432372e61707073706f742e636f6d2f6f2f6173736574732532462d4c55764a5566454d5767353248482d516f634f2532462d4c55764a625f5639766671476845557a32354c2532462d4c557651556e37584e4d357976693676635a59253246696d6167652e706e673f616c743d6d6564696126746f6b656e3d62613439393839342d656339352d346562622d613234662d333332393939666365396161)

## Flashing code onto the micro:bit
Duration: 3:00

Here is how to download your code onto the micro:bit editor:

Connect the micro:bit to your computer using a micro USB cable. Your micro:bit will show up on your computer as a drive called 'MICROBIT'. 

![screenshot](https://i.ibb.co/QvWrrNh/ezgif-com-video-to-gif.gif)

To download our code onto the microbit. Click the DOWNLOAD HEX button in the navigation bar at the top of EduBlocks. This will download a 'hex' file, which is a compact format of your program that your micro:bit can read. 

![screenshot](https://i.ibb.co/d2zrVgQ/Screenshot-2019-04-14-edublocks-8.png)

Once your code has downloaded, head over to your downloads folder where you'll see a file named `microbit-edublocks.hex`. Drag this onto the `MICROBIT` drive and you'll see a yellow flashing light on the back of your micro:bit. Once it's finished flashing, your code will now run!

![screenshot](https://i.ibb.co/j3H14WJ/ezgif-com-video-to-gif-1.gif)

## Flashing with webUSB
Duration: 4:00

If you run the chrome browser version 65+ and on Windows 10, Linux, macOS or Android, you can use a tool called webUSB to flash your micro:bit directly from the browser.

You need to have the latest firmware version on your micro:bit to be able to do this, to learn how to check this and update your firmware, [click here](https://support.microbit.org/support/solutions/articles/19000084059-beta-testing-web-usb)

To do this, load up some code in the micro:bit mode (look at the 'Load up a sample' step to find out how to do this).

Make sure your micro:bit is plugged into your computer, then, press the settings button in the top right hand corner.

![screenshot](https://i.ibb.co/JBbMsR2/Screenshot-from-2019-04-18-17-16-17.png)

This will load up the settings dialog, you'll see an option that says "Flash Hex", go ahead and press "Go" button next to it.

![screenshot](https://i.ibb.co/R74zt34/Screenshot-from-2019-04-18-17-17-50.png)

You'll now be able to see a dialog in the top left hand corner of chrome, select "BBC micro:bit CMSIS-DAP" from the list and click "Connect" to start flashing.

![screenshot](https://i.ibb.co/TvcZdyj/imageedit-1-2323001820.png)

The percentage dialog will go up as the file transfers to your micro:bit, you've now flashed your micro:bit via webUSB!

![screenshot](https://i.ibb.co/TBc24bB/Screenshot-from-2019-04-18-17-26-56.png)
