# Face-Mask-Detector-

Please read this README before running the code. You will find all information in order to run the code below. 
This programm is written for Python. 
The following versions have been used to run it: 
1. Python 3.8 from anaconda
2. Pycharm Community Edition
3. Microsoft vidual studios c++

Before running the code, please do the following: 
1. Download the folders "dataset" and "face_detector" as well as the document "requirements.txt" and safe it in a foalder (e.g. mask detector programm) on your computer
2. Download the necessary packages: open anaconda prompt and (i) enter "cd" and copy paste your working directory to the document " requirements.txt" and then (ii) enter "pip install -r requirements.txt" in order to install the packages defined in the requrements document
3. Open Pycharm and change your working directory to the folder created in step 1 (click on the right top on your file name -> edit configurator -> change your script path)
4. Choose your python intepreter as well (click on the right top on your file name -> edit configurator -> choose anaconda as python intepreter)
5. Change in the code your direction to the corresponding folder.
6. run the code train_mask_detector.py in order to train the model
7. Run the code detect_mask_video.py in order to use the trained program

The code will do the following: 
First (step6) it will train the face mask detector with the use of the labelled pictures saved in the folder "dataset". 
Then, you can apply the trained program in the following two ways: it will give you the choice to either activate your camera and check if you are wearing a face mask or upload a video to which the mechanism is applied. It furthermore indicated how sure it is. 
