# Linux OS for Miyoo/Bittboy handheld
![Alt text](miyoo.bmp)  
(Designed by win2next)
  
## Patch (20190217):
  1. kernel_20190217.zip(replace original r61520fb.ko in kernel folder)  
    + Fix compatible issue with pcsx rearmed emulator  
  2. pcsx_rearmed_20190217.zip  
    + Porting from notaz Github  
  3. gpsp_20190217.zip  
    + Fix crash when show setting menu  

## Patch (20190216):
  1. kernel_20190216.zip(replace original r61520fb.ko in kernel folder)  
    + Fix improper init code for lcd screen (issue: need reboot to enter GMenu2X)  
  2. miyoo_spi_hwmod_1bit_ghostkey_20190216.bin (flash via usb)  
    + Fix ghost key issue for SDCard 1Bit handheld (report nothing when the number of pressed key >= 3)  
  3. miyoo_spi_hwmod_4bit_ghostkey_20190216.bin (flash via usb)  
    + Fix ghost key issue for SDCard 4Bit handheld (report nothing when the number of pressed key >= 3)  
 
## Patch (20190214):
  1. Framebuffer driver: kernel_20190214.zip(replace original r61520fb.ko in kernel folder)  
    a. Support double buffer  
    b. Reduce screen flickering  
 
## V1.0 (20190203):
  1. First release  
  2. Framebuffer driver does not support double buffer  
  3. All of emulators/games/apps/gmenu2x are built without enabling double buffer  
  4. Included apps: commander  
  5. Included games: chocolate doom, sdlpal v1, sdlpal v2, sorr  
  6. Included emulators: fceux, gpsp, ohboy, picodrive, sms, snes9x4d, temper  
 
## Hotkey:
  1. Volume: Select + A/B  
  2. Backlight: Select + TA/TB  
 
## Poweroff:
  + Please run poweroff icon in GMenu2X and then switch off power button when black screen 
  + If you switch off power button directly, SDCard might corrupt due to sync issue
 
## Known issues:
  1. Ghost keys when press more than 3 keys  
  2. Need to double click DOWN key when start the game of sdlpal_v1/sdlpal_v2  
  3. Take about 5 seconds back to 60fps in sms emulator  
  4. Crash issue found in pcsx rearmed emulator when exit  
