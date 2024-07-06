# Arduino-Air-Mouse-using-Accelerometer-ADXL-335

This project allows you to control your computer mouse using an Arduino and an accelerometer. The mouse movement is based on the tilt of the Arduino, and it can also handle left and right mouse clicks.

## Components

- Arduino (any model)
- Accelerometer (e.g., ADXL335)
- Pushbutton
- Two additional buttons (for left and right clicks)
- Connecting wires
- Breadboard
  
## Setup

### Wiring

1. Accelerometer:
 - X-axis: A1
 - Y-axis: A2
 - Z-axis: A3
   
2. Buttons:
 - Pushbutton: Digital Pin 2
 - Left Button: Digital Pin 5
 - Right Button: Digital Pin 6

## Arduino Code

Upload the provided Arduino code to your Arduino board. The code reads data from the accelerometer and buttons, then sends the data to the computer via serial communication.

## Python Code

The Python script reads the data from the Arduino and moves the mouse accordingly using the pyautogui library.

## Requirements

- Python 3.x
- pyautogui library
  
## Installation

Install the pyautogui library:
```bash
pip install pyautogui
```
## Running the Code

1. Upload the Arduino code to your Arduino board.
2. Connect the Arduino to your computer via USB.
3. Run the Python script on your computer.
4. Tilt the Arduino to move the mouse cursor.
5. Use the left and right buttons to perform mouse clicks.
