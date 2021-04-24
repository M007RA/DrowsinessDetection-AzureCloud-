# Drowsiness Detection for Drivers using RPi

## Dependencies

1. Python 3
2. opencv
3. dlib	
4. imutils 
5. scipy
6. numpy
7. argparse

## Run 

```
Python3 drowsiness_yawn.py -- webcam 1		
```

## Note

Subject to changes
EYE_AR_THRESH = 0.3
EYE_AR_CONSEC_FRAMES = 30
YAWN_THRESH = 20	//change this according to the distance from the camera
shape_predictor_68_face_landmarks.dat needs to be downloaded via any public repository and the path for it must be specified in the python script



