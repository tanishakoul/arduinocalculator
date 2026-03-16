# Arduino Calculator

## Description
A basic calculator built using Arduino Uno, 4x4 keypad, and 16x2 LCD.  
It performs addition, subtraction, multiplication, and division.  
Keys A, B, C, D are used for operators, * for clear, and # for equals.

## Components
- Arduino Uno
- 4x4 Keypad
- 16x2 LCD
- Breadboard, jumper wires
- Arduino IDE

## How it works
1. Connect keypad and LCD to Arduino pins (see code for mapping).
2. Upload `calculator.ino` to Arduino using Arduino IDE.
3. Press numbers and operators on the keypad.
4. Result is displayed on the LCD.

## Example
Press: `2 A 3 #`  
LCD shows: `2+3 = 5`

## References
- Arduino LiquidCrystal library docs  
- Keypad library: https://github.com/Chris--A/Keypad
