# DE1-SoC Projects

## Introduction
This repository contains a collection of projects I have completed and am currently working on using the DE1-SoC development board. Each project showcases different features and capabilities of the board, providing hands-on experience with FPGA and SoC development.

## Table of Contents
1. [Simple Counter](#simple-counter)
2. [Calculator](#calculator-ongoing)
3. [Project 3](#project-3)

## Simple Counter
### Introduction
In this project, I followed the DE1-SoC "My First FPGA" guide, which can be found [here](http://www.ee.ic.ac.uk/pcheung/teaching/msc_experiment/My_First_Fpga.pdf).

### Project Details
Using Intel Quartus Prime, I implemented a simple counter on the DE1-SoC board. The counter increments every second and displays the count on the onboard LEDs.

### Conclusion
Through this project, I gained a deeper understanding of FPGA programming and the basics of digital design using Intel Quartus Prime.

### Demo
https://github.com/JuanCantu1/DE1-SoC-Projects/assets/109363196/fecd400f-9c70-4ee5-812c-b53407f53fb0

## Calculator "Ongoing"
### Introduction
This project involves using the DE1-SoC board to perform basic arithmetic operations (addition, subtraction, multiplication, division) on two base-10 numbers. The user will interact with the system through a computer console for number input and use the board's key buttons to select the arithmetic operation. The FPGA will handle input selection and display, while the ARM processor will handle the arithmetic operations using C.

### Project Details
#### 1. Input Number 1 from the Computer Console
- **Objective:** Input the first base-10 number from the computer.
- **Details:** 
  - Set up a serial communication link between the computer and the DE1-SoC board.
  - Implement a console interface to input a number.

#### 2. Choose the Operator Using Key Buttons
- **Objective:** Use the 4 key buttons on the DE1-SoC board to choose the arithmetic operation.
- **Details:** 
  - Key0: Addition
  - Key1: Subtraction
  - Key2: Multiplication
  - Key3: Division
  - Implement an FSM (Finite State Machine) on the FPGA to handle key press detection and debounce the input.

#### 3. Input Number 2 from the Computer Console
- **Objective:** Input the second base-10 number from the computer.
- **Details:** 
  - Utilize the same serial communication setup used for the first number.

#### 4. Perform the Arithmetic Operation
- **Objective:** Perform the selected arithmetic operation on the two input numbers.
- **Details:** 
  - Transfer the input numbers and the selected operation from the FPGA to the ARM processor.
  - Implement the arithmetic operations in C on the ARM processor.
  - Handle any potential division by zero errors gracefully.

#### 5. Display the Result on the Seven-Segment Displays
- **Objective:** Display the result of the arithmetic operation on the DE1-SoC board's seven-segment displays.
- **Details:** 
  - Convert the result to a format suitable for seven-segment display.
  - Implement the display logic on the FPGA to show the result.

### Conclusion
Upon completion, this project will provide a thorough understanding of both FPGA and ARM processor programming within the DE1-SoC platform. This hands-on experience will enhance my skills in embedded system design and development, preparing me for more complex projects in the future.

### Demo

## Project 3
### Introduction
(Provide a brief description of Project 3.)

### Project Details
(Describe what you did in Project 3, the tools used, and the outcomes.)

### Conclusion
(Summarize what you learned or achieved in Project 3.)

### Demo
(Include any relevant images, videos, or links to your demo for Project 3.)
