## Table of Content

- [How to do it?](#how-to-do-it)
    - [How to login and setup in git?](#how-to-login-and-setup-in-git)
    - [How to add date \& time in command prompt or terminal in windows PC?](#how-to-add-date--time-in-command-prompt-or-terminal-in-windows-pc)
    - [How to download PC Battery Report in windows 10/11](#how-to-download-pc-battery-report-in-windows-1011)
    - [How to turn off external devices wake up PC?](#how-to-turn-off-external-devices-wake-up-pc)
    - [How to import modules from different folders in python?](#how-to-import-modules-from-different-folders-in-python)
    - [How to open MS Store using Run?](#how-to-open-ms-store-using-run)

<br>

# How to do it?

### How to login and setup in git?

To add name - git config --global user.name "your_name" <br>
To add email - git config --global user.email "your_email"


### How to add date & time in command prompt or terminal in windows PC?

This 3 arrows is called prompt >>> in python or c:\Users\name> in windows terminal. For more information type **prompt /?**.

Once you decided the format we have to save it in registry editor. The format I chose is Date & Time | Path > 


### How to download PC Battery Report in windows 10/11

Open the cmd prompt as admin and type this command

```
powercfg /batteryreport /output "D:\battery_report.html"
```


### How to turn off external devices wake up PC? 

open device manager select _HID Keyboard Device & ID-compliant mouse_ go to Properties then select Power Management tab and uncheck **Allow this device to wake the computer**

### How to import modules from different folders in python?

Question: I have _person.py_ script inside the **JAN2024** folder and I have another folder called **FEB2024** which have _employee.py_ script I need to import _person.py_ script to use it as a base class of _employee.py_, how to import it in python?<br>
Note: both **JAN2024** and **FEB2024** folder are inside **Python** folder

Answer: The simplest way to add the file path in sys path for python to check the folder. In windows PC don't forget to add **\\\\** between folder hierarchy.

```python
import sys
sys.path.append('d:\\Github\\Python\\JAN2024')
from person import Person
```

### How to open MS Store using Run?

```
ms-windows-store:updates
```

### How to clear cache and temp files in windows PC?

Recursive Task for every month first day or week.
