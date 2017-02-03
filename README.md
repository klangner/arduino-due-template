# Minimal bare bone project for [Arduino Due](https://www.arduino.cc/en/Main/arduinoBoardDue)

C/C++ template with minimal project which can be compiled with standard GNU tools.
 
(But toolchain from Arduino installation.)

This template is based on information from:

http://www.atwillys.de/content/cc/using-custom-ide-and-system-library-on-arduino-due-sam3x8e


## Requirements

  * Arduino installation version 1.8+
  * Installation of Arduino Due board in Arduine IDE (This will download all toolchains and libraries in "~/.arduino15"). 
     

##  Compile and run
    
  * Clone the project
  * Modify **SAM_DIR** in Makefile to point to the toolchain installation.
  * Modify **TOOLS_DIR**  in Makefile to point to the tools installation.
  
  
## What is used from Arduino
  
All resources necessary for compilation:
  
  * Compiler: gcc/g++-arm-none-eabi
  * Flashing tool: BOSSA
  * Manufacturer libraries CMSIS "Cortex Microcontroller Software Interface Standard"
  * Atmel/SAM peripheral library
  * Linker command file