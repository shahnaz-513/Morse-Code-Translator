# Morse-Code-Translator
A device made with Arduino UNO and a 16x2 LCD display that converts Morse Code to letters and numbers. 

# Objectives
- Design and build a device that converts Morse code into letters and numbers.  
- Gain hands-on experience with Arduino UNO and LCD interfacing.  

# Theory 
Morse code encodes text using sequences of dots and dashes.  
Though modern communication methods have replaced Morse code in most applications, it is still used in **aircraft navigation**, **amateur radio**, and **emergency communication**.  

# Components Used
- 1 × Arduino UNO R3  
- 1 × 16x2 LCD Display (I2C module)  
- 6 × Push buttons (2 Pin & 4 Pin)  
- Breadboard, jumper wires, resistors  
- Screwdriver, tapes, scissors  

# Operation
1. Upload the Arduino sketch (`Morse_Code.ino`) using Arduino IDE.  
2. Connect the LCD and buttons as described in the report in the attached PDF in the repository 
3. Use the buttons for input:  
   - DOT (·), DASH (—), SPACE, ENTER, DELETE, RESET  
4. The decoded text appears on the LCD.  

# Circuit Diagram
- *Fig 1: Circuit diagram (Simulation)*  
- *Fig 2: Circuit diagram (Practical)*  

*(See attached PDF for detailed diagrams)*  

# User Manual
- `RESET` - Start/clear display  
- `DOT` / `DASH` - Input Morse code  
- `ENTER` - Confirm character  
- `SPACE` - Insert space  
- `DELETE` - Remove last character (must press ENTER after DELETE)  

*Buttons are sensitive – short press recommended.*  

# Implementation Challenges
- Display address detection issues (solved using I2C address finder).  
- LCD contrast adjustment required via potentiometer.  
- Sensitive button inputs.  
- Modified Arduino code to achieve the desired output.    
