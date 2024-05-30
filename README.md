# JediRemote
## “Control your TV with the Force!”

Jedi Remote is like a TV remote, except using a camera and only your hands. It uses a camera to capture and determine your gesture using visual processing. It currently recognizes six different hand gestures that correlate to the functions up, down, left, right, select, and return. When the camera detects one of the gestures, the screen reacts correspondingly. Jedi Remote eliminates the need for a physical remote, no need to stress over lost tv remotes.

__Roboflow Dataset__: https://app.roboflow.com/workspace-m7ft3/jedi-remote/deploy

## Resources
* Arduino Nano 33 BLE Sense Lite
* Arduino IDE
* Arduino OV7675 Camera Attachement
* USB Cable to connect Arduino to Computer

## Run Model
1) Install Arduino IDE, if not done so already including necessary libraries to use Arduino OV7675 camera
2) Download model.zip file from the repository
3) To add model library to Arduino IDE, go to Sketch->Include Library->Add .ZIP Library->model.zip
4) Open up the model code, go to File->Examples->Test_inferencing->nano_ble_sense->nano_ble_sense_camera
   <img src="https://github.com/vxw8/JediRemote/blob/main/Screenshot%202024-05-29%20223350.png" width="600" height="600">

5) Compile and upload code
6) Click on serial monitor to see predicted gestures
