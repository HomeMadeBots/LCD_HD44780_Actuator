# LCD_HD44780_Actuator

This repository defines a package gathering software elements allowing to manage a LCD device drived
by an HD44780.

The package is designed following
[this meta-model](https://github.com/HomeMadeBots/Embedded_Software_Meta_Model) and implemented
according to [these C language
patterns](https://github.com/HomeMadeBots/C-language-patterns-for-Embedded-Software-Meta-Model).

## Content

The LCD_HD44780_Actuator package gathers :
* Data_Types :
  * E_LCD_Config_Font
  * E_LCD_Config_Nb_Columns
  * E_LCD_Config_Nb_Lines
* Component_Types :
  * LCD_HD44780_4Bit_Actuator
  
## Overview

![Overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/LCD_HD44780_Actuator/master/doc/overview.puml)

## Dependencies

![Packages dependencies](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/LCD_HD44780_Actuator/master/doc/dependencies.puml)

The following repository shall be retrieved :
* [Hardware_IO_Interfaces](https://github.com/HomeMadeBots/Hardware_IO_Interfaces)
* [LCD_Interfaces](https://github.com/HomeMadeBots/LCD_Interfaces)
* [Bits_Management](https://github.com/HomeMadeBots/Bits_Management)
* [Embedded_C_Framework](https://github.com/HomeMadeBots/Embedded_C_Framework)

## Use

### With the Arduino IDE

This repository shall be clone within the _libraries_ folder of the _Arduino sketchbook folder_.