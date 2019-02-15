## MiOS:
### Linux OS for Miyoo/Bittboy handheld
  
## Patch (20190214):
  1. Framebuffer driver: kernel_20190214.zip(replace original r61520fb.ko in kernel folder)  
    a. Support double buffer  
    b. Reduce screen flickering  
 
## V1.0 (20190203):
  1. First release  
  2. Framebuffer driver lacks of the feature of double buffer  
  3. All of emulators/games/apps/gmenu2x build without enabling double buffer  
  4. Included apps: commander  
  5. Included games: chocolate doom, sdlpal v1, sdlpal v2, sorr  
  6. Included emullators: fceux, gpsp, ohboy, picodrive, sms, snes9x4d, temper  
 
## Hotkey:
  1. Volume(Select + A/B)  
  2. Backlight(Select + TA/TB)  
 
## Poweroff:
  + Please run poweroff icon in GMenu2X and then switch off power button when black screen 
  + If you switch off power button directly, SDCard might corrupt due to sync issue
 
## Known issues:
  1. Ghost keys when press more than 3 keys  
  2. Need to double click DOWN key when start sdlpal_v1 and sdlpal_v2  
  3. Take about 5 seconds back to 60fps in sms emulator  
  4. gpsp will hang when enter menu  
