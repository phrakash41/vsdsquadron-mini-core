# Task 1 Submission: Firmware Foundations & Environment Setup

## What is a firmware library?

A firmware library is a collection of pre-written functions that wrap up low-level, repetitive hardware operations into simple, reusable function calls.

## Why APIs are important in embedded systems?

APIs let embedded code say what it wants to do (like "turn on this pin") without needing to know how the hardware actually does it — making code easier, safer, and reusable across different chips.

## What was understood from the lab code?

The lab walked through a simple firmware library pattern: interface (.h) → implementation (.c) → application (main.c). 

gpio.h — declares the GPIO API (function names and constants) without saying how they work.  
gpio.c — implements those functions, simulating hardware behavior with printf instead of real registers.  
main.c — the application that uses the API to init pins, write the LED, and read the button, without knowing any hardware details.

## Build and run screenshot

![Successful compilation](task1_demo_output.jpg)

## Repository

GitHub repository link - https://github.com/phrakash41/vsdsquadron-mini-core/blob/main/task1/submission
