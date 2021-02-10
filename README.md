## Instalation ESP32

*    [Arduido IDE 1.8](https://www.arduino.cc/en/software)
*    Python
*    Pyserial

## Configuration

1. Add ESP32 Board Managers (File > Preferences > Copy(separated by commas): 
    *    https://arduino.esp8266.com/stable/package_esp8266com_index.json
    *    https://dl.espressif.com/dl/package_esp32_index.json
    *    https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
    *    https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.jso
2. Set Flash Frequency = 80MHz
3. Set Upload Speed = 115200

## About Coding

* There are differet terminals, in order to debug (if u are not using pro-ide) make sure you are executing ·Serial.begin(rate) with the same rate you have configured (in this case 115200) and open the debug terminal (Tools > Serial Monitor)
