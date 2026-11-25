🎲 Arduino Electronic Dice Using 7-Segment Display

Developed by Rajan Robotics
Vision to Reality

📌 Project Overview

The Arduino Electronic Dice is a simple electronics project that simulates a traditional six-sided dice using an Arduino Uno and a 7-segment display.

When the user presses a push button, Arduino generates a random number between 1 and 6 and displays the result on the 7-segment display.

This project introduces students to random number generation, digital input interfacing and 7-segment display control.

🎯 Objectives

- Generate random numbers between 1 and 6.
- Interface a 7-segment display with Arduino Uno.
- Read push-button input.
- Understand digital output control.
- Learn basic random number generation.

🧰 Components Required

S.No.| Component| Quantity
1| Arduino Uno| 1
2| Common Cathode 7-Segment Display| 1
3| Push Button| 1
4| 220Ω Resistors| 7
5| Breadboard| 1
6| Jumper Wires| As required
7| USB Cable| 1

🔌 Circuit Connections

7-Segment Display – Arduino Uno

The following connections assume a single-digit common-cathode 7-segment display.

Segment| Arduino Pin
a| D2
b| D3
c| D4
d| D5
e| D6
f| D7
g| D8
Common Cathode| GND

Important: Connect each segment through its own 220Ω current-limiting resistor. Identify the display pins using its datasheet.

Push Button – Arduino Uno

Push Button Connection| Arduino Pin
One terminal| D9
Other terminal| GND

The program can use Arduino's internal "INPUT_PULLUP" resistor, so an external pull-up resistor is not required.

⚙️ Working Principle

1. Arduino initializes the 7-segment display and push-button input.
2. The system waits for the user to press the button.
3. When the button is pressed, Arduino generates a random number from 1 to 6.
4. The corresponding number is displayed on the 7-segment display.
5. The user can press the button again to generate another number.

💻 Software Requirements

- Arduino IDE
- Arduino Uno board package
- USB cable

No external Arduino library is required.

✨ Features

- Random number generation from 1 to 6.
- Single-digit 7-segment display.
- Push-button-controlled operation.
- Simple and low-cost circuit.
- Beginner-friendly Arduino project.
- Useful for learning digital electronics.

🧪 Testing Procedure

1. Connect the 7-segment display according to the circuit diagram.
2. Connect the push button to Arduino pin D9.
3. Upload the Arduino program.
4. Press the push button.
5. Observe the generated number on the display.
6. Press again to generate another number.

🏠 Applications

- Electronic dice games.
- Educational electronics projects.
- Random number generation demonstrations.
- Arduino workshops.
- Beginner robotics experiments.

🚀 Future Improvements

- Add a rolling animation before displaying the result.
- Add a buzzer sound when the dice is rolled.
- Use a TM1637 4-digit display.
- Add an OLED display.
- Develop a two-player electronic dice game.
- Add a score-counting feature.

📁 Repository Structure

Arduino-Electronic-Dice-Using-7-Segment-Display/
│
├── Code/
│   └── Electronic_Dice.ino
│
├── Circuit/
│   └── circuit_diagram.png
│
├── Images/
│   └── working_prototype.jpg
│
├── Videos/
│   └── demo_video_link.txt
│
├── README.md
└── LICENSE

👨‍💻 Developed By

Rajan Robotics
Vision to Reality

Government Recognised Enterprise
UDYAM Registration: UDYAM-TN-27-0023934

Learn | Build | Innovate | Inspire

---

⭐ If you find this project useful, consider starring this repository!