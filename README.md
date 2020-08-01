
<a  href="https://pypi.org/project/PyHand-Earth"><img  src="https://i.ibb.co/X8KY0Ry/TopImg.png"  title="# PyHand-Earth"  alt="# PyHand-Earth"></a>
  

# PyHand-Earth 

  

>Welcome to <i>PyHand Earth</i>!


  

## Table of Contents 

 -  [Overview](#overview)
 -  [Special Comments](#comments)
 -  [Installation](#installation)
 -  [Start](#start)
 -  [Usage](#usage)
 -  [Team](#team)
 -  [License](#license)

---
  

## Overview

PyHand Earth is a Python-based software project that incorporates and integrates multiple high-performant concepts, libraries, tools, and techniques to optimize and maximize user experience in navigating the Google Earth Pro Desktop application relying only on simple hand gestures and an ordinary Webcam.

As a programming language, Python owes much of its popularity to its predilection for rapid deployment and to the ever-growing ecosystem of third-party open-source libraries and tools that add scalability, thereby freeing up precious time to more directly focus energies on solving the problems around us.  Yet, that type of flexibility comes with a price - which is paid in the currency of performance.  However, there is no shortage of high-performant tools and libraries that leverage all that Python has to offer with the inherent speed of these optimized solutions, many of which are written in high-performing languages such as C++.

Despite advances in computer vision and deep learning neural networks, there are not many open-source software deployments that advance hand-gesture recognition in any appreciable direction towards the kinds of user interfaces depicted in movies such as those in the Marvel universe ... think Tony Stark navigating a holographic interface.  Those that do exist seem to require the use of special hardware that includes depth sensors (e.g., Microsoft's Xbox Kinect and ultraleap's Leap Motion controllers).

This project serves as an attempt to take a first step towards user interfaces of the future but without such specialized hardware.


## Special Comments

For a smooth experience, users should review the following special comments, which include important instructions, tips, and suggestions.




## Installation

 ### Requirements

- Python 3.8 or higher 
- Compatible with Ubuntu 20.04


### Dependencies needed:

- Google Earth desktop (will be installed automatically if it is not already present in the environment)
- apt-get dependencies required to make pip installed packages work together 

```shell
$ sudo apt-get install python3-tk
```

Needed for pip installed pyautogui

```shell
$ sudo apt-get install libxcb-xinerama0
```
Required in order to start PyQt, which is pip installed

```shell
$ sudo apt-get install wmctrl
```
Necessary for us to manage certain windows

```shell
$ sudo apt-get install scrot
```
needed in order to locate images in the Google Earth application so that we can make sure it behaves properly

### Setup

  - This section will include all the `code` necessary to get  PyHand-Earth going
  
  #### Requirements: 
  
- TensorFlow 2.2.0
- OpenCV 4.2.0.34
- matplotlib 3.2.2
- Keras 2.4.2
- pyautogui 0.9.50
- PyQt5
- psutil 5.7.0



> install all requirements for PyHand-Earth with:

```shell

$ pip3 install PyHand-Earth

```

  OR

> install them individually with:

  

```shell

$ pip3 install opencv-python==4.2.0.34

$ pip3 install matplotlib==3.2.2

$ pip3 install --upgrade tensorflow==2.2.0

$ pip3 install Keras==2.4.2

$ pip3 install pyautogui==0.9.50

$ pip3 install PyQt5

$ pip3 install psutil==5.7.0

```





## Start 


#### To  Start PyHand-Earth:
- Navigate to the virtual environment folder, pip install pyhand-earth, then cd lib/python3.8/site-packages/PyHand-Earth/tyler/testing/new, then python3 [main_qt.py](http://main_qt.py/ "http://main_qt.py/")


```shell

$ python3 main_qt.py

```

- Two windows will show up:

	- Google Earth Pro: Targeted window to control with hand gestures
	
	- Gestures and buttons window : Demonstrating different possible gestures and buttons to start the OpenCV window video, Stop it and Exit the program which closes all the windows. 
	
### Initial view	
<img  src="https://i.ibb.co/k9MZSFp/two.png"  title="# PyHand-Earth"  alt="# PyHand-Earth"></a>

### Starting VIdeo

<img  src="https://i.ibb.co/X8KY0Ry/TopImg.png"  title="# PyHand-Earth"  alt="# PyHand-Earth"></a>


## Usage 

 
- This section will go over all menu buttons and functionalities.

### DISCLAIMER: Optimization of both of the programs has to be improved in order to make Google Earth more responsive. Model must be further developed to improve accuracy. 

 ### Buttons
<img  src="https://i.ibb.co/JqjgZPP/menu.png"  title="# PyHand-Earth"  alt="# PyHand-Earth"></a>

### DISCLAIMER: These are only preliminary hand gestures to demonstrate something in ... something out

 #### To Start Video:

![](https://s7.gifyu.com/images/start05a813aea53fe405.gif)

 #### To Stop Video:

![](https://s7.gifyu.com/images/stop6ee4ca56ae58c6da.gif)


  #### To Exit the Program:
 
![](https://s7.gifyu.com/images/end3dbe56bddb5bedae.gif)

---

  

## Team


- The PyHandlers team was formed for "CIS4930 - Performant Python Programming" from the University of Florida.

### Formed by:
- Grant H. Wise
- Tyler Allen
- Vanessa Orantes Murillo
- John Liu
- Ying Xu
 
---
  

## License

  

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

  

-  **[MIT license](http://opensource.org/licenses/mit-license.php)**

- Copyright 2020 © 
