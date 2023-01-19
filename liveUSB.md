# How to Create a Bootable Linux USB 
A Bootable Linux USB, or Live USB is a Linux operating system that can be run on any computer's hardware when plugged into the USB port.

## Step 1: Choose a Linux Distribution
There are many different versions of Linux, called **distributions**.  This guide will work with most distributions, but this guide will use **Ubuntu**.
## Step 2: Download the Disc Image
The disc image is an identical copy of the contents of a storage device.  Our image is stored as an **.iso** file that can be downloaded [here](https://ubuntu.com/download/desktop). 
## Step 3: Flash the USB
For this step, use [Balena Etcher](https://www.balena.io/etcher).

1. Plug in a USB drive. (**USB 3.0** is highly recommended)
2. Open Balena Etcher
3. Select **Flash from file** and choose the Ubuntu .iso file.
4. Under **Select target** choose your USB drive.
5. Click **Flash** and wait for the process to finish.

## Step 4: Enter the BIOS
The BIOS (basic input/output system) allows the user to select which storage device containing an OS will be booted. To do this, restart the computer and hold the [setup key](https://www.wikihow.com/Enter-BIOS). 

* Setup key may vary when using a PC
* **Option** key will always lead to BIOS on Mac

## Step 5: Boot the Live USB
In the startup menu, choose the live USB drive.

* This will usually be the only option other than the default.

Once it is selected, press the **Enter** key and Ubuntu will boot on the computer.
