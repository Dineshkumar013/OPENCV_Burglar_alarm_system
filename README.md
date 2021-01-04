# OPENCV_Burglar_alarm_system
In this project ,I have a made a alarm system which gives alert sound when an unknown moving is detected using opencv.

**APROACH**

The approach is very simple. When the program starts, we will capture a picture called baseline_image. This is the image without any object/intruder. Our program will keep comparing the new frame with this baseline_image. If nobody enters or exits the frame, there will be no difference. However, when somebody enters the frame, the contents of the image will be different and if this difference is beyond a certain threshold, our program will treat it as an intruder and play an audio.

 # STEPS
**1. Capture the baseline_frame (with no object)**

**1.1 Convert the frame to Gray**

**1.2 Smoothen the frame to remove noise**

**2. Capture the new_frame (with object)**

**2.1 Convert the frame to Gray**

**2.2 Smoothen the frame to remove noise**

**3. Calculate the difference between the two frames**

**3.1 If difference is greater than the threshold, assume motion is detected**

**3.2 Else assume no motion detected**
