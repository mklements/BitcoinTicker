# BitcoinTicker
Arduino code for my ESP32 based Bitcoin price ticker

# Connecting The Components On A Breadboard
| SSD1306 | ESP32 |
|-----|---|
| GND | GND |
| VCC | 3.3V |
| SLC | GPIO 22 |
| SDA | GPIO 21 |

# Library Used
- Adafruit_SSD1306.h [Here](https://github.com/adafruit/Adafruit_SSD1306)
- WiFi.h
- Wire.h
- HTTPClient.h
- NTPClient.h [Here](https://github.com/arduino-libraries/NTPClient)
- WiFiUdp.h
- ArduinoJson.h [Here](https://arduinojson.org/?utm_source=meta&utm_medium=library.properties)

# Schematic Diagram
![image](https://github.com/farrasrayhand/BitcoinTicker/assets/35839373/9a5a2735-7245-44c7-91ee-733862b86137)
You can simulate [Here](https://wokwi.com/projects/380207235932160001)

Source - https://www.the-diy-life.com/bitcoin-ticker-using-an-esp32-and-oled-display/

Price ticker kit available - https://www.etsy.com/au/listing/995022480/bitcoin-price-ticker-diy-kit
