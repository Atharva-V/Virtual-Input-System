# Virtual-Input-System
This program is created with OpenCV which is capable of simulating keyboard and mouse inputs virtually on camera with bare hands.
There two python files and a model file of (a-z) english alphabets.\n\n

->First is handtracker which uses mediapipline to track hand movement.\n
->Second is the main file.\n

## Basically there are 3 modes:\n
* Cursor moving mode
* Clicking mode
* Drawing mode ( this is where we draw, predict and input character)\n

## 1. Moving Mode
  Only index finger up moves mouse.
## 2. Clicking Mode
  Both index finger and middle finger up to go in click mode here moving stops and tap both fingers to click.
## 3. Drawing mode
  Open full palm and write character; recognizes only tip of index finger.\n
  To input written characte, close up or tap the thumb and the little  finger.\n
  To clear drawing in case to reset close whole palm and open again to begin drawing from start.\n
  
  # Here is a short video for demostration.
  

https://user-images.githubusercontent.com/74040947/138587649-53be3914-1b98-4ce1-8767-5e56b15f5f90.mp4

