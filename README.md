# Game-Center-Time-Calculation-Application
This application is designed for game centers with 10 PS4 and 10 PS5 devices. It helps calculate playtime costs for players using single or multiple joysticks. The app is built with PyQt5 and provides a user-friendly graphical interface.
## Features
1. Device Support: Tracks usage for up to 10 PS4s and 10 PS5s.
2. Cost Configuration: Set the cost per hour for single and multiple joystick setups.
3. Resolution Settings: Customizable resolution for your monitor.
4. Backup Files: Automatically saves the latest changes for smooth operation.
5. Easy-to-Use Interface: Interactive tables and buttons for managing timers and joystick configurations.
6. Executable File: Ready-to-use .exe for easy deployment.
## Structure
/exe/: Contains the precompiled executable file and necessary text files:

  1. GameCenter.exe: Run this file to launch the application.
  2. cost.txt: Configure hourly costs.
  3. resolution.txt: Set your system's resolution.
  4. back1.txt & back2.txt: Backup files for the application's last state.
  
/python_codes/: Contains the source Python code and text files for developers:
  1. Python scripts and the same set of text files.
## Prerequisites 
**To run the Python source code:**
<br> Python 3.x
<br> PyQt5 (pip install pyqt5)
## Configuration
Before using the app:
<br>Set Resolution:
<br>Open **resolution.txt** and update the numbers to match your system resolution (e.g., 1920,1080 for 1080p monitors).
<br>Set Hourly Costs:
<br>Open **cost.txt** and configure the hourly costs, separated by commas:
<br>ps4_single, ps4_double, ps4_triple, ps4_quad, ps5_single, ps5_double, ps5_triple, ps5_quad
<br>Example:
<br> 10,15,20,25,12,18,24,30
<br>ps4_single: Cost for 1 hour with a single joystick on PS4.
<br>ps4_double: Cost for 1 hour with 2 joysticks on PS4 and so on.
## Running the App
<br>Using the Executable:
<br>Go to the /exe/ folder and double-click GameCenter.exe to launch the GUI.
<br>Running the Source Code:
<br>Navigate to /python_codes/ and run the main script.
## Usage
**Launching the App:**
<br>Upon opening the app, you will see two separate tables:
<br>PS4 Table: Tracks usage for 10 PS4 devices.
<br>PS5 Table: Tracks usage for 10 PS5 devices.
<br>Setting Joystick Numbers:
<br>Use the 4 joystick buttons to configure the number of joysticks being used for each device.
<br>Starting the Timer:
<br>Press the Reset button at the top of the interface to start the timer for a selected device.
<br>Calculating Costs:
<br>At the end of the session, press the Calculate button to compute the cost based on the configured hourly rates.
<br>Backup and Restore:
<br>Changes are automatically saved to back1.txt and back2.txt to ensure data is preserved in case of interruptions.
