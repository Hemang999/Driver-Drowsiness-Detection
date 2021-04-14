# Driver-Drowsiness-Detection

Every year, thousands of people die in fatal road accidents around the world, and drowsy driving is one of the significant causes of death and injuries. Fatigue and micro sleeping at the wheel are often the cause of serious accidents. Drowsy driving must be detected early in order to avoid such incidents. Initial Drowsiness symptoms can be detected through the computer vision prototype system to monitor the Driver's attentiveness in real-time. As a result, a lightweight, real-time driver drowsiness detection system is developed and implemented on a webcam application in this report.

In this system, the Driver's images are acquired using the camera hardware available. From these images, facial detection is done and Machine learning algorithms are then used to classify drivers' vigilance.
   
Before deciding the driver's vigilance level, the system goes through a few measures. The face is first extracted from video frames using the face detector model. The location of the eyes and mouth is then identified through a shape predictor model. Finally, we use Mouth Aspect Ratio (MAR) and Eye Aspect Ratio (EAR) for detecting fatigue and drowsiness.
