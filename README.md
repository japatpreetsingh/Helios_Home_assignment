The aim of this take home assignment is to develop a traffic sign detection system with the help of Pytorch , that can detect and recognise traffic signs in real time .

The libraries that were used in this assignment are numpy , torch ,cv2 , torchvision matplotlib ,seaborn , PIL , pandas ,os , google.colab , torchsummary , prettytable , time ,datetime and sklearn .

In this project , a CNN model was created and trained on GTRSB Dataset on a Google Colab notebbok using T4 GPU . The trained model was then tested on the test dataset and after it had yielded satisfactory results , it was saved as "traffic_sign_detection.pth" .

For real time detection , the saved model was loaded into a jupyter notebbok on localhost . After loading the model , the video was captured using cv2.VideoCapture(0) in the form of frames . After the frames had been captured and preprocessed , the traffic sign was detected and predicted . 
