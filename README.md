# Digital-Clock-with-7-Segment-Display
Project Description
This project implements a simple digital clock using an Arduino and a 4-digit 7-segment display. The clock displays the current time in hours and minutes, and includes buttons to manually set the time. The clock is programmed to update every minute using the Arduino's millis() function to track time.

Features
Displays hours and minutes on a 7-segment display.
Two push buttons to set the hours and minutes.
Automatically increments the time every minute.
Components Required
Arduino (e.g., Arduino Uno)
4-Digit 7-Segment Display (Common Cathode or Anode)
Resistors (220Ω or 330Ω for segment current limiting)
Push Buttons (2x for setting hours and minutes)
Breadboard and Jumper Wires
Circuit Diagram
 (Insert the actual path to your circuit diagram image here)

Segment Pins (A-G) are connected to Arduino pins 2-8.
Digit Control Pins are connected to Arduino pins 9-12.
Push Buttons are connected to Arduino pins 13 (Hour) and 14 (Minute) with one side to ground.
Setup and Usage
Connect the Circuit: Follow the circuit diagram to connect your 7-segment display, buttons, and Arduino.
Upload the Code: Load the provided Arduino sketch to your Arduino board.
Set the Time:
Press the "Hour" button to increment the hours.
Press the "Minute" button to increment the minutes.
Operation: The clock will start keeping time and display the current hours and minutes.
Code Overview
The Arduino code manages the time using the millis() function, updates the 7-segment display, and handles button presses to set the time. The display is multiplexed to show each digit, with a short delay for visibility.

Future Improvements
Add Seconds Display: Extend the code to display seconds.
Use RTC Module: Implement a Real-Time Clock (RTC) module for more accurate timekeeping.
Alarm Feature: Add an alarm function with an additional button to set the alarm time.
License
This project is open-source and available under the MIT License.
