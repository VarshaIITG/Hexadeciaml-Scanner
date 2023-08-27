# Hexadecimal Keypad Scanner Verilog Project

This Verilog project implements a Hexadecimal Keypad Scanner. It is designed to scan a 4x4 keypad and detect the pressed keys, which are then converted to their corresponding hexadecimal values.

## Project Overview

The project consists of the following components:
- 4x4 keypad matrix interfacing.
- Keypad scanning and debounce logic.
- Conversion of pressed keys to hexadecimal values.

## Features

- Scans a 4x4 matrix keypad for pressed keys.
- Utilizes debounce logic to avoid false key detections due to bouncing.
- Converts pressed keys to their corresponding hexadecimal values (0-9, A-F).

## Files

- `Hexadecimal_Keypad_Scanner.v`: Main Verilog module for the project.
- `Hexadecimal_Keypad_Scanner_Tb.v`: Testbench Verilog module for the project.
- `Hex_Keypad`: Module for detecting the key pressed.
- `Row_Sig`: Module to detect Row.
- `Synch`: Module fort synchronizer.


### Simulation

1. Open the simulation tool provided by your Verilog IDE.
2. Add the project files and the testbench.
3. Compile and simulate the design.
4. Observe the waveforms to verify the functionality of the keypad scanner.


