# CODTECH Internship - task 1

Name : Chandan A
Company : CODTECH IT SOLUTIONS Pvt. Ltd.
ID : CT6WTWE
Domain : Embedded Systems
Duration : February 20th, 2025 to April 5th, 2025
Mentor : Neela Santhosh

# Project Title
Push Button Counter

# Project Overview
The Push Button Counter is an embedded system designed to count the number of button presses and display the count on a 16x2 LCD.  
The project uses an Arduino Uno microcontroller to handle the counting logic and LCD interfacing.  

# Key Features
1. Button Press Counter:  
   - Increments the count by 1 every time the button is pressed.  
2. LCD Display:  
   - Displays the updated count in real time on a 16x2 LCD.  
3. Debouncing Mechanism:  
   - Prevents false triggers due to noise or multiple presses.  
4. Reset on Restart:  
   - The counter resets when the device is powered off or restarted.  

# Components Used
- Microcontroller: Arduino Uno  
- Push Button Switch  
- LCD Display (16x2 i2c)  
- Power Supply: 5V  
- Breadboard and Jumper Wires  

# Working Principle
1. When the push button is pressed, the Arduino detects the input signal.  
2. The counter increases by 1 on each valid press.  
3. The updated count is displayed on the LCD.  
4. Debouncing is implemented to prevent multiple counts due to a single press.  

# Applications
- Event Counter: Counting attendees or button presses.  
- Visitor Counter: For libraries, offices, or public areas.  
- Tally System: Counting objects or signals.  

# How to Run
1. Assemble the Circuit:  
   - Connect the push button, LCD, and Arduino as per the circuit diagram.  
   - Ensure proper power supply and connections.  
2. Upload the Code:  
   - Use the Arduino IDE to upload the .ino file.  
3. Power the Circuit:  
   - Apply 5V power.  
   - Press the button to see the count increment on the LCD. 

# Troubleshooting
1. No Display on LCD:  
   - Check the contrast potentiometer settings.  
   - Ensure proper I2C connections and address.  
2. Incorrect Counting:  
   - Add a debounce delay in the code to avoid false triggers.  
3. No Response from Button:  
   - Verify the button connections and resistor placement.  

# Contributing
Contributions are welcome!  
If you have any improvements or bug fixes, feel free to fork the repository and submit a pull request.  

# License
This project is licensed under the MIT License.

![circuit_diagram ](https://github.com/user-attachments/assets/4474bc4e-a0d7-4e07-bfea-95759a51fe42)

