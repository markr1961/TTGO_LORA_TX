# TTGO_LORA_TX
TTGO LoRa32 SX1276 OLED: ESP32 development board with SX1276 LoRa chip and SSD1306 0.96 inch OLED display.

adapted from an example by Rui Santos, https://RandomNerdTutorials.com/ttgo-lora32-sx1276-arduino-ide/

board:      LillyGO TTGO LoRa32-OLED
libraries:  
  Adafruit SSD1306  https://github.com/adafruit/Adafruit_SSD1306
  Adafruit GFX      https://github.com/adafruit/Adafruit-GFX-Library
  LoRa by Sandeep Mistry  https://github.com/sandeepmistry/arduino-LoRa

Most boards operate in either the 433MHz or 866/915MHz bands.
The existing code sets the 866MHz band which is not legal in North America.
