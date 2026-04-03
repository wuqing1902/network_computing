# Lab Module 2: Everything Becomes Programmable

## Overview

The labs in this module focuses on programming IoT devices using visual programming (Blockly) and Python. Students explore how to control hardware outputs such as LEDs and RGB LEDs using Blockly in Cisco Packet Tracer, and gain foundational skills in Python programming, including variables, loops, conditional statements, input handling, and simple algorithm implementation. The module bridges visual programming for IoT and text-based programming for general-purpose applications, providing hands-on experience in controlling devices and creating interactive programs.

---

## Objective

By the end of Module 2, students will be able to:
- Understand and apply visual programming concepts (Blockly) to control IoT devices.
- Program LEDs and RGB LEDs using digital and analog outputs.
- Develop basic Python scripts in IDLE to perform calculations, manipulate data, and receive user input.
- Implement simple algorithms and create interactive programs or games.
- Demonstrate programming logic and problem-solving skills through practical exercises.

---

## Lab 1: Blink an LED Using Blockly (Packet Tracer)
### Description
This lab introduces Blockly programming within Cisco Packet Tracer to control IoT devices such as single-colored and RGB LEDs. Students modify prebuilt programs to observe LED behavior and learn to programmatically manipulate hardware outputs.
### Objective
- Examine a prebuilt Blockly program.
- Control a single-colored LED using digital and analog outputs.
- Program an RGB LED to display different colors using multiple pins.
### Tools and Methods
- Cisco Packet Tracer with Blockly support
- MCU (Microcontroller Unit)
- Single-color LED and RGB LED
- Blockly visual programming
### Key Tasks Performed
- Examined the functionality of a prebuilt LED program.
- Changed digital output to analog output to control LED brightness.
- Added an MCU and RGB LED, connecting pins appropriately (Red, Green, Blue).
- Programmed sequences to display individual and combined RGB colors.
### Technical Insight
- Learned how digital and analog outputs affect LED behavior.
- Gained understanding of controlling multiple pins simultaneously for RGB LEDs.
- Practiced translating visual block logic into hardware action.
### Result / Findings
- LED blinked when the correct digital value was used.
- AnalogWrite allowed adjustment of LED brightness.
- RGB LED displayed RED, GREEN, and BLUE in sequence; combining outputs allowed color mixing.
### Skills Demonstrated
- Blockly programming and logic sequencing
- IoT device integration and pin mapping
- LED control and debugging techniques

---

## Lab 2 – Basic Python Programming
### Description
This lab introduces Python programming fundamentals. Students practiced arithmetic operations, data types, string manipulation, variables, type conversion, and user input in an interactive Python environment (IDLE).
### Objective
- Practice basic Python syntax and commands.
- Learn data types and type conversions.
- Create simple scripts using IDLE.
### Tools and Methods
- Python 3 / IDLE
- Interactive Python shell
- Python scripts (.py files)
### Key Tasks Performed
- Installed Python 3 and configured IDLE.
- Executed arithmetic operations and printed strings.
- Created and manipulated variables.
- Used type() to identify data types.
- Converted between integers, floats, and strings.
- Received user input and printed custom messages.
- Created and ran simple Python scripts (Hello World, calculations).
### Technical Insight
- Learned Python’s dynamic typing and basic syntax rules.
- Practiced debugging and testing simple Python scripts.
- Understood how interactive Python shell differs from script execution.
### Result / Findings
- Successfully executed calculations and string manipulations.
- Created scripts that run in IDLE and produce expected outputs.
- Learned to capture user input and display custom messages.
### Skills Demonstrated
- Basic Python programming
- Script creation and execution
- Data type handling and type conversion
- Debugging and problem-solving

---

## Lab 3 – Create a Simple Game with Python IDLE (Integrated Development and Learning Environment)
### Description
In this lab, students create a number-guessing game using Python IDLE. The game implements the bisection method to find a user-selected number, teaching logic, loops, conditional statements, and input validation.
### Objective
- Implement a simple game using Python.
- Practice conditional logic, loops, and arithmetic operations.
- Handle user input validation.
### Tools and Methods
- Python 3 / IDLE
- Scripts (.py files)
- Bisection algorithm logic
### Key Tasks Performed
- Created a new Python script in IDLE.
- Programmed a number-guessing game using loops and if-else statements.
- Implemented input validation for numbers outside the 0–1024 range and non-integer inputs.
- Ran the game and tested various scenarios for correctness.
### Technical Insight
- Learned to implement bisection algorithm in Python.
- Practiced input validation techniques using string methods and conditional checks.
- Developed logic for loops and nested if-else statements.
### Result / Findings
- Game correctly guesses numbers selected by the user.
- Input validation ensures only integers between 0–1024 are accepted.
- Game logic demonstrates efficient searching using bisection method.
### Skills Demonstrated
- Python programming with loops and conditionals
- Algorithm implementation (bisection method)
- Input validation and debugging
- Script execution in IDLE

---

## Reflection

The labs highlights the importance of programming in IoT and general software development. Using Blockly allowed me to visualize logic flow and see real-time effects on IoT devices, reinforcing the relationship between code and physical outputs. Python exercises provided insight into scripting, data types, and debugging techniques, emphasizing how programming can automate tasks, validate inputs, and implement efficient algorithms. The simple number-guessing game showcased how logic and loops work together to solve problems effectively. Overall, this module strengthened my confidence in both visual and text-based programming while demonstrating their practical applications in IoT and software development.

---

## Conclusion

The labs successfully demonstrates the integration of programming skills with IoT and Python fundamentals. Through hands-on exercises, students develop practical skills in controlling devices, creating scripts, and solving problems using algorithms. The combination of Blockly and Python provides a well-rounded foundation for further exploration in IoT development, automation, and software programming. This module emphasizes critical thinking, logical reasoning, and the ability to translate concepts into functional programs, preparing students for advanced projects and real-world applications.
