# Pico-Alarm-Clock
###### Pin outs and in's for pico based alarm clock 

#### OLED SSD1306

| GP0 -> SDA | GP1 -> SCL | VCC -> VCC | GND -> GND |

#### RTC DS1307

| GP2 -> SDA | GP3 -> SDA | VCC -> VCC | GND -> GND |

#### BUTTONS

| GP15 -> UP Button <- VCC | GP14 -> DOWN Button <- VCC | GP13 -> SELECT Button <- VCC |

#### ALARM

| GND -> Cathode | GP16 -> Annode |


## Basic Instructions
**!! MAKE SURE TO ADD PULL DOWN RESISTORS TO THE BUTTONS !!**

Use the select button from the time display screen to get into menus
