# stm32-ssd1306
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fvookimedlo%2Fstm32-ssd1306.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fvookimedlo%2Fstm32-ssd1306?ref=badge_shield)


**stm32-ssd1306** project is aimed at the SSD1306 based 128x32 OLED display connected over I²C to the STM32F1x MCU.

Original code was taken from Tilen Majerle.
- https://github.com/MaJerle/stm32fxxx-hal-libraries
- 865b030b8bec70d3e1ed6251f845884143189d99

Changes in the *stm32-ssd1306:*
- updated to be based on the original STM32 HAL Drivers.
- initial SSD1306 was fixed and updated to the 128x32 OLED display.
- code cleaned-up and aligned to the C11.
- expected SSD1306 I²C address is ```0x3C```, could be changed by re-defining ```SSD1306_I2C_ADDR``` macro.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fvookimedlo%2Fstm32-ssd1306.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fvookimedlo%2Fstm32-ssd1306?ref=badge_large)