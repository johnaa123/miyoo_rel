**MiOS:**
  Linux OS for Miyoo/Bittboy handheld

**patch (20190214):**
  1. framebuffer driver: kernel_20190214.zip(replace original r61520fb.ko in kernel folder)
    a. support double buffer
    b. reduce screen flickering

**v1.0 (20190203):**
  1. first release
  2. framebuffer driver lacks of the feature of double buffer
  3. all of emulators/games/apps/gmenu2x build without enabling double buffer
  4. included apps: commander
  5. included games: chocolate doom, sdlpal v1, sdlpal v2, sorr
  6. included emullators: fceux, gpsp, ohboy, picodrive, sms, snes9x4d, temper

**Hotkey:**
  select + A/B: adjust volume
  select + TA/TB: adjust backlight

**How to do poweroff:**
  please run poweroff icon in GMenu2X and then switch off power button when black screen

**Known issues:**
  1. ghost keys when press more than 3 keys
  2. need to double click DOWN key when start sdlpal_v1 and sdlpal_v2
  3. take about 5 seconds back to 60fps in sms emulator
  4. gpsp will hang when enter menu
