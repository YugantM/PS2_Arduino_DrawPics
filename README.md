# Drawing Pictures (PS2 + Arduino)

## This is the list of components required for the given project:

### * Arduino UNO
### * PS2 Mouse
### * 12 V DC Adapter (recommended)
### * OLED display (I2C interface 128 x 64)
### * USB cable
### * 1.5 meter wire or 15 jumper cables 
<hr>

## Project description:

### * The PS2 connector has a pin for Data and another pin for Clock and using only these two pins the mouse communicate with the host device.

![image](https://static-cdn.imageservice.cloud/737533/a-essentials-tutorial-personal-computer-components-ports-and-cables.jpg)

### * The code for this project uses the PS2 library file called “PS2Mouse.h” which has all the necessary routines for accessing a PS2 mouse. 
### * There are two functions which the user can directly make use in their code and are namely “mouse.initialize()” and “mouse.report(data)”.


<hr>

# Schematic diagram:
<img src="schematic.jpeg" alt="step1" style="float: left; margin-right: 10px;" />
<hr>

# Bread board view:
<img src="breadboard.jpeg" alt="step1" style="float: left; margin-right: 10px;" />
