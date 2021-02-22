# Browser AutoInstaller for Windows
Remember the days where you have to reset 30 PCs and manually install Google Chrome and Firefox in preperation to Tabletop Exercise? Is ***"Manual Work"*** tiring? Fear no more for we, the 3 interns in TP (Temasek Polytechnic), Keh Shao Xuan, Lee Chun Yong and Boo Yan Cong, have developed a python script to take care half the job!

Browser AutoInstaller is basically as what it is, installing Firefox and Google Chrome automatically upon the click of the executable.

All you have to do is to insert the thumbdrive into a PC and run a.exe to automatically install Google Chrome and Firefox in ***1 click***! We even lazily named our executables and python script!
(Just remember to put the a.exe, ChromeSetup.exe and FirefoxInstaller.exe into the Thumbdrive)

## How to compile python code to exe
1. Install pyinstaller (pip3 install pyinstaller)
2. pyinstaller --onefile a.py
3. The exe is located at currentdirectory/dist

## Reminders
Please remember to update the ChromeSetup.exe and FirefoxInstaller.exe to the latest version. As this was done months ago, the browsers exe's are now outdated.

## Some idea for future enchancement
Find a way to evade the tamper protection and make it such that the script automatically runs upon inserting the thumbdrive into the PC.