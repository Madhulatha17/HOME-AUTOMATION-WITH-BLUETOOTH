# HOME-AUTOMATION-WITH-BLUETOOTH

## Project Overview

This project demonstrates a simple Home Automation System using Arduino Uno. The system allows a device to be switched ON and OFF using command inputs. Due to the limitations of the Tinkercad simulation environment, Bluetooth communication is simulated through the Arduino Serial Monitor.

## Objective

To design and simulate a home automation system capable of controlling electrical devices remotely through command-based communication.

## Components Used

* Arduino Uno
* Arduino IDE (Tinkercad Code Editor)
* Built-in LED (Pin 13)
* Serial Monitor

## Working Principle

The Arduino continuously monitors incoming serial commands.

* Command `1` turns the device ON.
* Command `0` turns the device OFF.

In this simulation, the built-in LED on Arduino Pin 13 represents a home appliance.

## Circuit Design

The project uses the Arduino Uno built-in LED connected to Digital Pin 13.

No external components are required for the simulation.

## Arduino Code Functionality

1. Initialize serial communication at 9600 baud rate.
2. Read commands from the Serial Monitor.
3. Turn the device ON when command `1` is received.
4. Turn the device OFF when command `0` is received.
5. Display status messages on the Serial Monitor.

## Simulation Procedure

1. Open the circuit in Tinkercad.
2. Start the simulation.
3. Open the Serial Monitor.
4. Enter `1` and click Send.
5. Observe the LED turning ON.
6. Enter `0` and click Send.
7. Observe the LED turning OFF.

## Sample Output

```text
Device ON
Device OFF
Device ON
```

## Applications

* Home Automation Systems
* Smart Lighting Control
* IoT-Based Device Management
* Remote Switching Applications

## Limitations

Tinkercad does not provide full Bluetooth module simulation. Therefore, Bluetooth communication is represented using Serial Monitor commands. In a real-world implementation, an HC-05 Bluetooth module can be connected to Arduino to receive commands wirelessly from a smartphone.

## Files Included

* home_automation_bluetooth.ino
* circuit_diagram.png
* output_demo.png
* README.md

## Outcome

Successfully simulated a Bluetooth-controlled home automation system using Arduino Uno and Tinkercad, demonstrating device ON/OFF control through command-based communication.
