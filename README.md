# ESPSmartBed
Smart Bed using ESP8266 and integrated scale via HX711
Version 1.0 Notes:
- LED resistor seems to cause issues.  Use a wire instead of a resistor.
- Some HX711 sensors seem to be defective.  Not sure how to test ahead of time...
- circuit board can be uploaded to JLCPCB and you can order 10 for like $8 plus shipping.
- circuit board positive and negative nets are undersized for lots of LEDs.  Should be increased in later revisions..

Parts List:
- ESP8266 (Wemos D1 Mini Clone)
- HX711 (with 4 sensors each) - can handle up to 3 (3 HX711s and 12 sensors)
- Up to 3 MCP23008 chips for additional inputs and outputs (buttons etc)
- Slots for 8 buttons on the board (tied into one of the MCP23008) - not tested yet.



Inspired by:
https://synapselabs.io/posts/bed-sensor-with-esphome-on-homeassistant/
https://www.reddit.com/r/homeassistant/comments/856yav/i_made_a_stupidly_accurate_bed_occupancy_sensor/
https://everythingsmarthome.co.uk/howto/building-a-bed-occupancy-sensor-for-home-assistant/

![Custom Bed with WS2812B LEDs](/Photos/20210827_151237.jpg)

![Circuit Board](/Photos/20210920_184517.jpg)

![Case](/Photos/20211001_162814.jpg)

![Case Mounted](/Photos/20211001_165858.jpg)

![Final Result](/Photos/20210828_215434.jpg)




