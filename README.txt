##### (You) Pokerbot - README #####
- This script requires python 3.6 or higher
  https://www.python.org/downloads/

##### INFORMATIONS #####
- The game must be set to the smallest size (first "diamond" on the game bottom bar, or go in the settings)
- Only compatible with the english language 


##### INSTALLATION #####
- Some python modules must be installed to run this script, follow those steps (for Windows):
1) Start Menu > Search cmd > open the command prompt
2) Type 'pip'.
3) Install those modules with those commands (Right click to paste in cmd):
    pip install pyautogui
    pip install numpy
    pip install opencv-python-headless
    pip install Pillow
    pip install keyboard
    pip install pywin32

##### USAGE #####
- click poker.pyw and start a poker game 

##### SETTINGS #####
- Edit settings.json with a notepad :
time_limit = time limit in second before stopping (default: 3600)
sound_alert = to enable the sound alert (default: true)
sound_file = sound file used by the capcha alert (WINDOWS ONLY) (default: "alert.wav")

A new file is generated if it's missing.

##### HOTKEYS #####
- Escape : Stop and exit the script
- F7 : toggle Pause/Resume (the script will finish its current action before pausing)
