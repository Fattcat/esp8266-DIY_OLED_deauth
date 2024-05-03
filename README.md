# esp8266-DIY_OLED_deauth EDITED


# INSTALLATION

- Clone this repo.
- Unzip your downloaded .zip (with WinRAR or something else).
- Go to --> esp8266_deauther folder and open Arduino file "esp9266_deauther".
- Select correct COM Port of your esp8266 and select board name "NodeMCU".
- HIT UPLOAD BUTTON
- Wait  1 - 2 min (it depends on how fast your PC is xD)
- After sucessfully uploaded code unplug your esp8266 and FOLLOW CONNECTION INSTRUCTIONS.
# CONNECTION INSTRUCTIONS

## esp8266 --> 0.96" OLED Display
- 3.3V  --> VCC
-  GND --> GND
-  SCL  --> D2
-  SDA  --> D1
-  In some cases you need to switch from SCL --> D2, SDA --> D1 to SCL --> D1, SDA --> D2 (just switch pins iu your OLED not showing anything ...)
## esp8266  --> Buttons
- D5  --> Button UP
- D6  --> Button DOWN
- D7  --> Button ENTER

## Allow OLED DISPLAY on WEB INTERFACE
- after sucessful programming and connecting you must visit WEB INTERFACE for allow OLED to work with esp8266
1. Power your esp8266 then CONNECT TO WiFi "pwned" with password "deauther".
2. go to 192.168.4.1 and hit that button with accepting conditions with using it.
3. next go to SETTINGS (TOP RIGHT CORNER) and scroll down to the end of page and SELLECT OLED BUTTON to TRUE then click on SAVE button (TOP LEFT CORNER) and hit REBOOT button (TOP RIGHT CORNER)
4. Your esp8266 will be rebooted after some time and thhen u good to go
# thats it and thats all u need to know.
## Support me and @spacehuhn by hitting on STAR ICON :D
# THX For reading this guide
## creds to github.com/spacehuhn
## creds to github.com/Fattcat
