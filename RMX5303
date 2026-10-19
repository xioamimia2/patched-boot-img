
# Magisk patched boot.img 
> Patched boot.img images for systemless root on XIOAMI MI A2 

Ready-to-use boot.img for installing Magisk.

## Disclaimer
    /*
     * Your warranty is... still valid?
     *
     * I am not responsible for bricked devices,
     * thermonuclear war, or you getting fired because the alarm app failed. Please
     * do some research if you have any concerns about features included in this tutorial
     * before flashing it! YOU are choosing to make these modifications, and if
     * you point the finger at me for messing up your device, I will laugh at you.
     */
     
## Requisites
* Unlocked bootloader
* ADB/FASTBOOT Drivers
* USB Cable
* [Latest Magisk Manager.apk](https://github.com/topjohnwu/Magisk/releases)
* [corresponding patched boot.img](https://github.com/xioamimia2/patched-boot-img/releases/latest)

## Installation

1. Install the latest Magisk Manage directly from GitHub's project (link above).
2. Reboot your device to bootloader/fastboot mode.
*This can be done powering off you phone and then press VOL- and POWER at the same time -or- Connect you phone with USB Debugging enabled, open a Command Prompt window and type:*

	```
	adb reboot bootloader
	```
	*- Now your phone now should reboot in bootloader/fastboot mode*

3. Check your device gets recognized by your pc, type:

	```
	fastboot devices
	```

	> HELP! My phone doesn't shows up! What should I do?
	
	***Check your drivers** and try again*


## Direct install

You can flash patched boot.img directly to your phone:
  

> **ATTENTION! Use your phone's version (check under Settings-> About-> Compilation number),** using the wrong one may have unwanted results.

  
  ```
  fastboot flash boot_a replace-with-correct-path/V.X.X.XX.X.ODIMIFE-PATCHED.IMG
  fastboot flash boot_b replace-with-correct-path/V.X.X.XX.X.ODIMIFE-PATCHED.IMG
  ```
  
  (where X's are your phones compilation number)
  
  
  Now reboot you phone:
 ```
 fastboot reboot
 ```
 
That's it!
 
##  Magisk Manager Install (Safest method)
*This is the recommended method. If something goes wrong, rebooting your phone should get everything back to normal*


> **ATTENTION! Use your phone's version (check under Settings-> About-> Compilation number),** using the wrong one may have unwanted results.
  
  ```
  fastboot boot replace-with-correct-path/V.X.X.XX.X.ODIMIFE-PATCHED.IMG
  ```
  
  Your phone will reboot itself.


Now your phone should have booted normally but now with **magisk temporarily** installed, please check ***everything is working.*** *(Camera, Wi-FI, Bluetooth, Calls... Everything else)*

> **If somethig is not working correctly just reboot your phone.**
> 
If everything is working as expected, open Magisk Manager and **Press Install** ->  Install -> **Direct Install (Recommended)**.




Wait until Magisk does all the work...

Press **Reboot**.

That's it!
