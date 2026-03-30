# Hermes
A simple CLearning crossover. This repository is part of CLearning's ecosystem and was made to help other tool's development. If you find it useful, use it. In summary, Hermes is a simple header-only console managment library with various stop and clear functions.  
By the way, it's called Hermes because that guy was gods' messenger just like this lib helps you communicate with the user in an easier way  

## Functions
- **Stop(void)**: Will stop the console until the user presses a enter.
- **StopM(char msg)**: Will stop the console and display a custom message.
- **clearUntil(void)**: Will stop the console and clear once the user presses enter.
- **clearConsoleM(char message)**: Will clear the console and show a custom message.
- **clearConsole(void)**: Will simply clear the console.
- **readLine(void)**: Will read the new line in console (stdin)

## Technical data
- It's designed for **both windows and linux/mac**

## Install instructions
Download it from this repository and add the header to your project or use `cl -i hermes` in your console if you have CLearning installed

### Version
1.0.1 - Console Manager
Author: Nahum Naranjo