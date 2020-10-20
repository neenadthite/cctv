# cctv
The project demonstrates converting a system on chip (SoC) into cctv camera transmitter. Key features includes online monitoring over the internet, audio monitoring, motion detection, buzzer alarm, android app, monitoring multiple cameras, no coding required etc. The project was tested using Raspberry Pi 3 B. The hardware and software used for the project are provided below.

Hardware: USB webcam/camera module, Raspberry Pi 3, USB sound adapter, 3.5 mm jack speaker and microphone, wi-fi router/ethernet connection, SD card, card reader
Software : Lineage OS 16 (Android 9), Alfred home surveillence android apk, 7 zip, Raspberry Pi imager, SD card formatter.

On Camera side,
Step 1: Download lineage os image file https://konstakang.com/devices/rpi3/LineageOS16.0/ 
Step 2: Format SD card using SD card formatter, Extract Lineage OS 16 .img file using 7 zip, Write .img file on SD card 
Step 3: Plug in Camera. Insert SD card in Raspberry Pi 3 and setup the OS for first time
Step 4: Plug in USB sound adapter, connect speaker and microphone to it
Step 5: Download and install Alfred - Home Security Camera .apk file https://alfred.en.uptodown.com/android (Allow installation from unknow sources in setting) 
Step 6: Open Alfred - Home Security Camera, Sign up/in, switch to Camera (from Camera/Viewer). In settings check "Reopen app automatically" 
Your Pi is ready to transmitt. 

On Viewer side,
Download the Alfred Camera .apk on android or visit website https://alfred.computer . Sign in from the same account, switch to viewer and view your camera.
Options are provided in the graphical user interface (GUI) for motion detection, buzzer alarm, flash on/off, enable/disable audio input.
In case on motion detection, events are also stored for 7 days inside the app.


