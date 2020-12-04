# Face-Mask-Detector-

Please read this README before running the code. You will find all information in order to run the code below. 
This programm is written for Python. 
The following versions have been used to run it: 
1. Python 3.8 from anaconda
2. Pycharm Community Edition
3. Microsoft visual studios c++

Before running the code, please do the following: 
1. Download the folders "dataset" and "face_detector" as well as the document "requirements.txt" and safe it in a foalder (e.g. mask detector programm) on your computer
2. Download the necessary packages: open anaconda prompt and (i) enter "cd" and copy paste your working directory to the document " requirements.txt" and then (ii) enter "pip install -r requirements.txt" in order to install the packages defined in the requirements document
3. Open Pycharm and change your working directory to the folder created in step 1 (click on the right top on your file name -> edit configurator -> change your script path)
4. Choose your python intepreter (click on the right top on your file name -> edit configurator -> choose anaconda as python intepreter)
5. Change your direction in the code to the corresponding folder
6. Run the code "train_mask_detector.py" in order to train the model
7. Run the code "detect_mask_video.py" in order to use the trained programm

The code will do the following: 
First (step 6) it will train the face mask detector with the use of the labelled pictures saved in the folder "dataset". 
Then, you can apply the trained program in the following two ways: it will give you the choice to either activate your camera and check if you are wearing a face mask or upload a video to which the mechanism is applied. It furthermore indicates the percentage of certainty whether it detects a face mask or not. 

This programm is based on the face mask detector by Balaji Srinivas https://github.com/balajisrinivas/Face-Mask-Detection
It has been enhanced with different functionalities. User input in order to choose if the face mask detector should use the webcam or a video has been added. Additionally, the user can choose to safe the output. 
