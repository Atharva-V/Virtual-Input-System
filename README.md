# Virtual-Input-System 
This is a HCI( Human Computer Interaction) project program created with OpenCV which is capable of simulating keyboard and mouse inputs virtually on camera with bare hands (Virtaul-Mouse-virtual-keyboard-writing).\
There two python files and a model file of (a-z) english alphabets.

->First is handtracker which uses mediapipline to track hand movement.\
->Second is the main file.

## Basically there are 3 modes:
* Cursor moving mode
* Clicking mode
* Drawing mode ( this is where we draw, predict and input character)

## 1. Moving Mode
  Only index finger up moves mouse.
## 2. Clicking Mode
  Both index finger and middle finger up to go in click mode here moving stops and tap both fingers to click.
## 3. Drawing mode
  Open full palm and write character; recognizes only tip of index finger.\
  To input written characte, close up or tap the thumb and the little  finger.\
  To clear drawing in case to reset close whole palm and open again to begin drawing from start.\
  
Use this to get project:
```
git clone https://github.com/Atharva-V/Virtual-Input-System
```
  
  # Here is a short video for demostration.
  



https://user-images.githubusercontent.com/74040947/138587749-a6c4b839-928f-482d-9ff8-3d6841198bae.mp4

