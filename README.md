# FaceMaskDetector
This is a machine learning project that is a real time face mask detector using Python, OpenCV, Keras, TF, numpy and matplotlib.



Technical/ Software Requirements :
Tensorflow >=1.15.2
Keras ==2.3.1
Imutils ==0.5.3
Numpy ==1.18.2
opencv-python ==4.2.0.*
Matplotlib ==3.2.1
Scipy ==1.4.1
Windows XP and above

You can install these using the command pip install –r requirements.txt


In order to train the model, open cmd in the desired path of your project and use the command
python train_mask_detector.py

This will train your model and give the training loss and accuracy curve


In order to use model in real time camera use the command
python detect_mask_video.py
