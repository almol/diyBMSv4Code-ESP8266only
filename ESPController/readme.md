# ESP Controller

It talks to the V4.X cell modules over isolated serial bus. This code runs on ESP-8266 WEMOS D1 (Mini or Pro) and compiles with VS CODE and PLATFORM IO environment

## LEDs
### Green LED
- blinks when communication received
- turns on while booting for 3 seconds, to set high the WIFI Reset PIN to reconfigure the AP Settings

### Blue LED (on WeMos)
- Serial communications


### FORK almol.
Fork from: https://github.com/stuartpittaway/diyBMSv4Code

Remove PCF8574 and use only two relays on D5 and D6 output.


