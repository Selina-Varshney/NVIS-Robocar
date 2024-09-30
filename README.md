# NVIS-Robocar (Buggy)
A project made by Selina Varshney

This project aimed at creating a line follower buggy robot, which would follow a track equipped with 3 gantries. The buggy would stop at each gantry and finally at the end of the track. This was a group project where I learned how to design a transmitter, receiver and IR sensor module using Autodesk Eagle and then soldered all components onto the breadboard to create each circuit. These were then attached to the buggy. We then wrote an arduino code to move the buggy in our own specified directions  like left, right, forward, backward, clockwise and anti clockwise by setting the pins 5, 6, 7, 8 on Nvis 3302ARD RoboCar accordingly to either high or low as per the logic required. 

For reference kindly see the demo video.

1. Designing & Testing Transmitter Circuit:
   The transmitter circuit generates rectangular pulses of specific pulse width for IR emitter corresponding to each Gantry.
<div>
   <image src="https://github.com/user-attachments/assets/ff5568f4-63a8-46e2-8d59-09bb42695fbd" width=500 height=300>  <image src="https://github.com/user-attachments/assets/54ebc53c-f731-459a-b414-757340933a74" width=500 height=300>
   </div>

2. Designing & Testing Receiver Circuit:
The receiver circuit can sense the signal of IR pulse from a specific gantry and able to recognize it based on respective pulse width.
<div>
   <image src="https://github.com/user-attachments/assets/bc4a1f57-596f-42bc-b9a2-d16f4f84116b" width=500 height=300>  <image src="https://github.com/user-attachments/assets/292fe5d8-db06-43e1-8968-86afafc8a732" width=500 height=300>
   </div>

3. Designing & Testing IR sensor circuit:
IR sensor module circuit helps Buggy robot to move on a predefined path as a line follower.
<div>
   <image src="https://github.com/user-attachments/assets/981af4c0-b28f-486f-b214-762bf4a1847c" width=500 height=300>  <image src="https://github.com/user-attachments/assets/961b0ad0-f0b5-4f76-bd1a-96fa86723c4d" width=500 height=300>
   </div>



