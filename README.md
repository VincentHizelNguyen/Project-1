# Project-1
<h1 align="center">HAND GESTURE RECOGNITION</h1>
<p align="center">
</p>

## ✅About

This is a personal project for the Project 1 course at The School of Information and Communication Technology. The project is a software that has 4 functions that can be controlled by hand gestures: light bulb, computer speaker, computer mouse, and fan. 

The project was written in Python language and uses Mediapipe to detect hand gestures.

Here are some important parameters of Mediapipe that we need to pay attention to:

<table>
  <tr>
    <td><code><b>max_num_hands</b></code>: The maximum number of hands can be detected by the GestureRecognizer.</td>
  </tr>
  <tr>
    <td><code><b>min_detection_confidence</b></code>: The minimum confidence score for the hand detection to be considered successful.</td>
  </tr>
  <tr>
    <td><code><b>min_tracking_confidence</b></code>: The minimum confidence score for the hand tracking to be considered successful.</td>
  </tr>
</table>

## 📌Requirements

Firstly, to ensure that the program can run smoothly, I recommend that you install these libraries before we begin.

And don’t forget that your computer needs a webcam to be able to use this program!

```
pip install pillow 
pip install opencv-python 
pip install mediapipe 
pip install pycaw 
pip install comtypes 
pip install numpy 
pip install pyautogui
```

## 🛠️Installation

After you’ve installed the requirements, you can clone this repository to your local disk. Then, simply run the `main.py` file to enjoy the program experience.

## 📙How to use (Program Tutorial)

As I mentioned earlier above, this program includes 4 functions, and each function has a different usage.

REMEMBER: If you want escape the program, just simply press `Esc` on your keyboard.

### 💡Light Bulb Control (max_num_hands=1):

To control the light bulb function, you need to know that each light bulb corresponds to one of your fingers. When you raise a finger, the light bulb depends on it will turn on, and when you lower that finger, the light bulb will turn off.

**Light Rule:**

| Finger | Light color |
|:------ | -----------:|
| Thumb  | Yellow🟨    |
| Index  | Red 🟥      |
| Middle | Green 🟩    |
| Ring   | Blue 🟦     |
| Pinky  | Orange 🟧   |

📍Example:

<img title="" src=".github\media\light_control_example.gif" alt="" width="547" data-align="center">

### 🔊Volume Control (max_num_hands=2):

This function allows you to control the overall sound on your computer. By raising your thumb and index finger, you can increase or decrease the volume according to the distance you create between these two fingers. The farther apart your fingers are, the louder the volume will be, and vice versa.

📍Example:

<img title="" src=".github\media\volume_control_example.gif" alt="" data-align="center" width="547">

### 🖱️Mouse Control (max_num_hands=1):

When you activate this function, a blue rectangle frame will appear on your webcam. This blue frame represents the resolution of the screen you are using. To control the mouse cursor, simply raise and move your index with middle finger in the frame. If you want to click the mouse, you can bend your index finger quickly at the position where you want to click. Just pretend you are clicking a real computer mouse.

📍Example:

<img title="" src=".github\media\mouse_control_example.gif" alt="" data-align="center" width="547">

### 𖣘 Fan Control (max_num_hands=1):

For the fan control function, all you need to do is clench your hand to turn off the fan and open all 5 fingers to turn on the fan. (Note: All 5 fingers must be open for the fan to turn on!)

📍Example:

<img title="" src=".github\media\fan_control_example.gif" alt="" data-align="center" width="547">


## 📝References:

- [Gesture recognition task guide  MediaPipe| Google for Developers|](https://developers.google.com/mediapipe/solutions/vision/gesture_recognizer)

- [mediapipe/docs/solutions/hands.md at master · google/mediapipe · GitHub](https://github.com/google/mediapipe/blob/master/docs/solutions/hands.md)

- [Nhận diện chuyển động cử chỉ bàn tay với OpenCV - Hand Tracking](https://ngoton.it/nhan-dien-chuyen-dong-cu-chi-ban-tay-voi-opencv-hand-tracking/)

- [AI Virtual Mouse](https://www.youtube.com/watch?v=8gPONnGIPgw&t=267s)

- [Mouse and keyboard automation using Python - GeeksforGeeks](https://www.geeksforgeeks.org/mouse-keyboard-automation-using-python/)

- [Distinguish Between Right and Left Hands in MediaPipe](https://toptechboy.com/distinguish-between-right-and-left-hands-in-mediapipe/)

- [How to show webcam in TkInter Window - Python - GeeksforGeeks](https://www.geeksforgeeks.org/how-to-show-webcam-in-tkinter-window-python/)

- [How to controll LED| OpenCV Python l](https://www.youtube.com/watch?v=fwMjVZhM08s&t=253s) 
