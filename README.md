# STM32-LED-Sequencing
My first STM32  project – Sequential LED Chaser using STM32 NUCLEO-F401RE, 5 LEDs, and STM32CubeIDE. Implemented GPIO control to create a running LED effect using Embedded C.
# STM32-Based Sequential LED Chaser

A simple embedded systems project that demonstrates sequential LED blinking using the STM32 NUCLEO-F401RE development board. Five LEDs turn ON and OFF one after another, creating a running light effect.

## Overview

This project implements a Sequential LED Chaser using the STM32 NUCLEO-F401RE microcontroller. Five LEDs are connected to GPIO pins through current-limiting resistors. The STM32 controls the LEDs sequentially using GPIO output operations and programmed time delays.

## Key Features

- Controls 5 LEDs using STM32 GPIO pins
- Turns LEDs ON and OFF sequentially
- Creates a running LED light effect
- Uses programmed time delays to control LED speed
- Demonstrates digital output control using STM32

## System Design

Five LEDs are connected to the GPIO pins of the STM32 NUCLEO-F401RE board through current-limiting resistors. The microcontroller controls each LED independently. Using GPIO programming and time delays, the LEDs turn ON and OFF one after another in a continuous sequence.

## Hardware Components

| Component | Quantity | Purpose |
|---|---:|---|
| STM32 NUCLEO-F401RE | 1 | Main microcontroller |
| LED | 5 | Produces the sequential running light effect |
| Resistors | 5 | Limits current through the LEDs |
| Jumper Wires | As required | Hardware connections |
| Breadboard | 1 | Circuit assembly |

## Software and Tools

- Microcontroller: STM32 NUCLEO-F401RE
- Programming Language: Embedded C
- IDE: STM32CubeIDE
- Peripheral: GPIO

## Source Code

The STM32CubeIDE project source code is included in this repository.

## Project Photos

![STM32 Sequential LED Chaser](Images/sq_led.jpeg)

## Project Demonstration Video

[Watch the STM32 Sequential LED Chaser Demonstration](YOUR_VIDEO_LINK_HERE)

## How It Works

1. Five LEDs are connected to the STM32 GPIO pins through resistors.
2. The STM32 configures the GPIO pins as output pins.
3. The first LED turns ON, followed by the second, third, fourth, and fifth LEDs.
4. Each LED turns OFF according to the programmed sequence.
5. The sequence repeats continuously to create a running LED effect.

## How to Build and Run

1. Connect five LEDs to the STM32 NUCLEO-F401RE board through resistors.
2. Open STM32CubeIDE.
3. Configure the required GPIO pins as output.
4. Write the Embedded C program to control the LEDs sequentially.
5. Build and compile the project.
6. Upload the program to the STM32 board.
7. Observe the sequential LED running effect.

## Skills Learned

- STM32 Microcontroller Programming
- Embedded C Programming
- GPIO Configuration and Control
- STM32CubeIDE
- Digital Electronics
- Hardware Interfacing

## Future Improvements

- Adjustable LED running speed
- Multiple LED patterns
- Bidirectional LED chasing
- Button-controlled LED sequences

## Team and Contributions

- Meenakshi Sundaram — Designed and implemented the project independently.
