# Python Alarm Clock

## Project Description
This Python program allows the user to set an alarm for a specific time. Once the alarm time is reached, the program plays a sound or displays a notification. The program uses the `datetime` module to track the current time and `time.sleep()` to reduce CPU usage by avoiding constant checking.

## Features
- Allows the user to set an alarm in `HH:MM:SS` format.
- Continuously checks the current time against the set alarm time.
- Plays a sound (or triggers a notification) when the alarm time is reached.
- Uses `time.sleep()` to avoid excessive resource usage while waiting.

## How It Works
1. The user inputs the alarm time in `HH:MM:SS` format.
2. The program continuously compares the current time (using the `datetime` module) with the user-defined alarm time.
3. When the current time matches the alarm time, the program plays a sound or triggers a notification.
4. The program uses `time.sleep(1)` to wait for one second between each time check to avoid constant CPU use.

## Requirements
- Python 3.x
- No external dependencies (uses built-in `time` and `datetime` modules)

## How to Run the Script
1. Clone or download the project.
2. Open a terminal or command prompt in the project directory.
3. Run the following command:
   ```bash
   python alarm_clock.py
