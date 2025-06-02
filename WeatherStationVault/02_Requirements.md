### Data logging frequency:
- photo every 3 hours
- log data every 2 minutes
- store in CSV-file every day (720 data points for one day)

### Sensors:
- Temperature and Humidity Sensor
- Photoresistor for measuring light
- Realtime clock for accurate dates
- camera (images take about 1 MB of storage)

### Storage:
- MicroSD card

### Power supply:
- 


### Libaries:
- DHTLib
- RTClib : [https://github.com/adafruit/RTClib](https://github.com/adafruit/RTClib)
- Wire (#include <Wire.h>)
- define custom I2C pins in software for ESP32, for using RTC (DS3231 I2C)