# Firmware Installation Guide

## Prerequisites
- Download and install [Arduino IDE](https://www.arduino.cc/en/software/)
- During first launch, allow Arduino IDE to install drivers when prompted

## Setup

1. Open [sketch_promicro.ino](https://github.com/multifex/prototypes/blob/main/jasp-keyboard-joystick/firmware/sketch_promicro.ino) in Arduino IDE
2. Plug your Pro Micro into your PC
3. In the Arduino IDE board dropdown, select **Arduino Leonardo**

## Install the Joystick Library

1. Go to [github.com/MHeironimus/ArduinoJoystickLibrary](https://github.com/MHeironimus/ArduinoJoystickLibrary)
2. Click **Code → Download ZIP**
3. In Arduino IDE, go to **Sketch → Include Library → Add .ZIP Library**
4. Select the ZIP you downloaded

## Compile & Upload

1. Press the **checkmark icon** to compile the firmware
2. Press the **arrow icon** to upload it to your board

## Verify It's Working

1. Open the Windows Start menu and search for **"Set up USB game controllers"**
2. **Arduino Leonardo** should appear in the list
3. Click **Properties** and confirm the analog joystick is responding

## Game Compatibility

Some (probably most) games may not recognize the joystick directly. If that happens, try one of these key remappers:

- [AntiMicroX](https://github.com/antimicroX/antimicroX) — maps joystick inputs to keyboard/mouse
- [x360ce](https://github.com/x360ce/x360ce) — emulates an Xbox 360 controller
