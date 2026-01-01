# Educational Security Research: Keyboard Hooking

### ⚠️ WARNING
This project is for **educational and ethical security research purposes only**. 
The use of this code for tracking keystrokes on a computer without 
explicit permission is **illegal and unethical**.

## Description
This script demonstrates how the `pynput` library can be used to interface 
with system-level keyboard events. It is intended to help developers 
understand how keyloggers function so they can build better defenses.

## How it Works (Logic Flow)
The script initializes a listener that captures every physical key press 
and writes the character to a local buffer, which is then appended to a file.



## Precautions
- **Run in a VM:** Only run this code in a controlled Virtual Machine.
- **Data Privacy:** Be aware that this will log your own sensitive data if active.
- **Legal:** Use this knowledge only for white-hat security testing.