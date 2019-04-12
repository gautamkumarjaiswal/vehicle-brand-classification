# car-brand-prediction
Recognize brand of car using deep learning (multiclass classification)

NOTE: WE WILL CREATE VIRTUAL ENVIRONMENT AND INSTALL ALL DEPENDENCIES IN THAT SO THAT IT WILL NOT CHANGE/AFFECT YOUR ROOT DIRECTORY, JUST BY DELETEING THIS FOLDER YOU CAN DELETE ITS EXISTANCE.

open windows 'cmd' typing cmd in search (not conda command window) as an administrator



1) Download and install python from> https://www.python.org/downloads/    (if you already have then ignore this step and check its version to be sure)
2) check python version> python -V

3) Install virtual environment> pip install virtualenv
4) test installation> virtualenv --version

5) Download folder from the drive link and extract it to 'C' drive and rename this folder to 'Brand_prediction', if already renamed then please ignore.
At this time if you open 'Brand_prediction' folder it would contains some files and folder like dataset,examples,cnnmodel, classify.py,train.py, brandNet.model etc.


6) Now change the directroy to 'Brand_prediction' folder
(at this type your command prompt window should look like C:\Brand_prediction>)

7) create virtual environment repositery>virtualenv env
(this will create a folder with name 'env' inside working reositery 'Brand_prediction')

8) Run the command to activate virtual environment>env\Scripts\activate

(after successful run, cmd window will look like '(env) C:\Brand_prediction>' means you have successfully created and activated virtual env and ready to work)




##### Install necessary packages ####################


9) Now install Keras by typing: (env) C:\traffic_classification>pip install keras
(this may take few minutes)
10) Install tensorflow using pip: (env) C:\Brand_prediction>pip install --upgrade tensorflow
11) Install keras using pip : (env) C:\Brand_prediction>pip install keras
12) Install opencv using pip : (env) C:\Brand_prediction>pip install opencv-python
13) Install sklearn using pip : (env) C:\Brand_prediction>pip install sklearn
14) Install matplotlib using pip : (env) C:\Brand_prediction>pip install matplotlib 
15) Install imutils using pip : (env) C:\Brand_prediction>pip install imutils


##########  NOW YOU ARE READY To Test SCRIPT  ##############################

16) Issue this command:(env) C:\Brand_prediction>python classify.py --model brandNet.model --labelbin lb.pickles --image examples/bmw1.jpg
(make sure 'bmw1.jpg' image is inside 'examples' folder, otherwise it would give error)

To Re-train CNN Model

17)run the python scipt: (env) C:\Brand_prediction>python train.py --dataset dataset --model brandNet.model --labelbin lb.pickles


HAPPY CODING
