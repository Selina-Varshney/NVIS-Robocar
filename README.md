# NVIS-Robocar (Buggy)

1. Designing & Testing Transmitter Circuit:
   The transmitter circuit generates rectangular pulses of specific pulse width for IR emitter corresponding to each Gantry.
<div>
   <image src="https://github.com/user-attachments/assets/ff5568f4-63a8-46e2-8d59-09bb42695fbd" width=500>  <image src="https://github.com/user-attachments/assets/54ebc53c-f731-459a-b414-757340933a74" width=500>
   </div>
![image](https://github.com/user-attachments/assets/ff5568f4-63a8-46e2-8d59-09bb42695fbd | width=100) ![image](https://github.com/user-attachments/assets/54ebc53c-f731-459a-b414-757340933a74)


3. Designing & Testing Receiver Circuit:
The receiver circuit can sense the signal of IR pulse from a specific gantry and able to recognize it based on respective pulse width.
![image](https://github.com/user-attachments/assets/bc4a1f57-596f-42bc-b9a2-d16f4f84116b)
![image](https://github.com/user-attachments/assets/292fe5d8-db06-43e1-8968-86afafc8a732)

4. Designing & Testing IR sensor circuit:
IR sensor module circuit helps Buggy robot to move on a predefined path as a line follower.
![image](https://github.com/user-attachments/assets/981af4c0-b28f-486f-b214-762bf4a1847c)
![image](https://github.com/user-attachments/assets/961b0ad0-f0b5-4f76-bd1a-96fa86723c4d)

Working: After attaching these sensors onto a Nvis RoboCar and using Arduino to write the code logic, the buggy could follow a black track,
and move in our own specified directions like left, right, forward, backward, clockwise and anti clockwise by setting the pins 5, 6, 7, 8 on Nvis 3302ARD RoboCar accordingly to either high or low. The buggy would also stop at each gantry, and finally stop after completing the track. 

For reference kindly see the demo video.
