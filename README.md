# Athany: a python application to remind you of your purpose

<br>

### قال تعالى: {وَمَا خَلَقْتُ الْجِنَّ وَالْإِنسَ إِلَّا لِيَعْبُدُونِ (56)} \[الذاريات]

<br>
 
#### Athany is a python program for windows and linux that fetches the times for the five mandatory muslim prayers, tells you the time remaining until the next prayer and plays the athan sound if the prayer time comes.
 
<br>
 
## Requirements
 
- Python3 (tested on python 3.10 & 3.11)

- `tk` tkinter package if you're on linux, install it using your package manager. If you can't find it, search how to install tkinter on your distro.

- `PySimpleGUI` python module

- `psgtray` python module

- `requests` python module

- `simpleaudio` python module

- **If you're not using windows**, the following modules are required to correctly display arabic text
  - `python-bidi`
  - `arabic-reshaper`

## Installation

1. Install tkinter (`python-tk` on debian-based, `tk` on arch-based) using your package manager if you're on Linux, if you're on Windows you don't need this step.

2. `git clone https://github.com/0xzer0x/athany-app` or download the code as zip from GitHub

3. Download the _Athans.zip_ file from [here](https://drive.google.com/file/d/1AKKsRSePFuPBuzRieIB8hZjAZ7ywzimc/view?usp=sharing)

4. Extract the audio files from the zip file into the **Data** directory/folder

5. **If you're on linux**, Download Required [Fonts](https://drive.google.com/file/d/1rTb6EHN6WFZjVJLiFJN3YbMqsdAqZtnf/view?usp=sharing) for application. Copy fonts to /usr/share/fonts/

6. Open a terminal, browse into the "athany-app" folder

7. run `pip install -r requirements.txt`

8. run `python athany.py`
