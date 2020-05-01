# Blinky 📸
A Python Selfie App that captures selfies at the blink of your eyes ;)

## Installation

### Requirements

  * Python 3.6+
  * OpenCV 3.4+ 
  * imutils
  * dlib
  * scipy

## Download the model:
[shape_predictor_68_face_landmarks](https://drive.google.com/file/d/1i5bJtlstVU5dZpZ_4eCo0wAceg-7Cs2K/view?usp=sharing)
Save this in the model folder

### Usage
Run app.py on the terminal
```bash
python3 app.py
```
![](https://github.com/AshwinRaikar88/Blinky/blob/master/output/demo.gif?raw=true)
* Just blink both your eyes to capture an image
  the app will close automatically
* If you want to quit, just press 'q'

The image will be saved in output directory.

### Further improvements
*  New funtionalities will be added
*  This program was successfully tested on windows

## Thanks 
Thanks to [@rishikksh20](https://github.com/rishikksh20) for his code on Liveness-Detection, the module that helps in implementing blink detection.
