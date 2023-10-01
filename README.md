# stm32f051r8tx_2x16LCD_Display

# Description
	Using STM32F051 control and display text on the 2x16 LCD(qapass lcd)
	LCD have two coummunication mode (8 bit & 4 bit)
	Because the schematic is quite a bit difficult to describe so in the 'about lcd' folder i contain the schematic and other thing related to lcd.
# pin connection

## STM32F051 DISCOVERY KIT      						LCD
// COMMUNICATION PURPOSE
	if mode 8 PORT A PIN0->PIN3							D0->D3
	PORT A PIN4->PIN7									D4 -> 7
// CONTROLLING PURPOSE
	PORT C PIN 0 -> PIN 3								RS-RW-E
	