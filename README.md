# Drowsiness-Detection
 A high performance drowsiness detection system using OpenCV and Dlib that detects the states of sleepiness, drowsiness and activeness based on Dlib's 68-point facial landmark detector.
Facial landmarks are used to localize and represent salient regions of the face, such as:
- Eyes
- Eyebrows
- Nose
- Mouth
- Jawline

In this project I have utilised the long distance between the points 36 and 39 and the 2 short distances between the points 37 and 38 and the points 40 and 41 for the left eye. Th ratio between the distances are used to determine the state of the driver. The schematic representation of the facial landamrks:
<img src="68landmarks">

## Output
<img src = "Outputs/output.gif">
