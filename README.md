# Arduino Three-Phase Pump Starter with Tank Level Monitoring

## Table of Contents

1. [Introduction](#introduction)
2. [Components Required](#components-required)
3. [Circuit Diagram](#circuit-diagram)
4. [Arduino Code](#arduino-code)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

---

## Introduction

This Arduino project provides a comprehensive solution for controlling a three-phase pump to fill a tank while monitoring the tank's water level using a 16x2 LCD display. The system includes features such as automatic start and stop based on the tank's water level and protection against phase outage using a three-phase protector.

Key features of this project include:

- Automatic pump start when the tank is empty.
- Automatic pump stop when the tank is full.
- Continuous monitoring of the water level displayed on a 16x2 LCD.
- Three-phase protector to prevent phase error.

This README will guide you through the necessary components, circuit setup, Arduino code, and usage instructions to build and operate this project.

---

## Components Required

To build this project, you will need the following components:

1. Arduino board (e.g., Arduino Uno)
2. 16x2 LCD display
3. Three-phase starter circuit
4. Three-phase protector
5. Water level sensor (e.g., float switch or ultrasonic sensor)
6. Three-phase pump motor
7. Breadboard and jumper wires
8. Power supply for the pump motor
9. Tank or container for water storage
10. Electrical wiring and connectors

Make sure you have all these components ready before proceeding.

---

## Circuit Diagram

![Circuit Diagram](https://www.tinkercad.com/things/iuqoMybtrDk)

Please refer to the provided circuit diagram for wiring instructions. Ensure that all connections are secure and that safety precautions are followed when working with electrical components.

---

## Arduino Code

The Arduino code for this project can be found in the "arduino_code" directory. You will need to upload this code to your Arduino board using the Arduino IDE. Before uploading, make sure to configure the necessary parameters in the code, such as pins for the water level sensor, LCD display, and other settings according to your specific hardware setup.

---

## Usage

1. **Hardware Setup**: Follow the circuit diagram to connect all the components properly.

2. **Arduino Code Configuration**: Open the Arduino code in the Arduino IDE and configure it according to your specific hardware setup. Be sure to set the correct pins for the water level sensor, LCD display, and other parameters.

3. **Upload Code**: Upload the modified Arduino code to your Arduino board.

4. **Power On**: Power on the system, and the Arduino will initialize.

5. **Operation**:
   - The system will start the pump when the tank is empty based on the water level sensor's input.
   - It will stop the pump when the tank is full.
   - The LCD display will continuously show the current water level and system status.

6. **Monitoring**: Keep an eye on the LCD display for water level and system status updates.

7. **Safety Precautions**: Always exercise caution when working with electrical components. Ensure that all connections are secure and that the three-phase protector is functioning correctly to prevent overloading.

---

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements or encounter any issues, please create a GitHub issue or submit a pull request.

---

## License

This project is open-source and available under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as per the terms of the license.

---

Thank you for using our Arduino Three-Phase Pump Starter with Tank Level Monitoring project. I hope it serves your water management needs effectively! If you have any questions or need assistance, please don't hesitate to reach out.


