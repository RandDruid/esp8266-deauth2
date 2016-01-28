# esp8266-deauth2
Multi target De-Auth attack implementation for Two ESP8266 modules.

(project with only 1 module - https://github.com/RandDruid/esp8266-deauth)

Projected was created in Arduino IDE v. 1.6.7.
Support for ESP8266 was added with Board Manager. Look here: https://github.com/esp8266/Arduino
I used version 2.1.0-rc2 with edited user-interface.h. Basically I took declaration for 'wifi_send_pkt_freedom' function from higher version of SDK (1.5.0) and paste it into SDK 1.3.0 (because I can see this function present in binaries)

Project page on hackaday.io: https://hackaday.io/project/9333-weekend-on-the-dark-side
