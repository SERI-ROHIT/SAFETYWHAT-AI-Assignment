# SAFETYWHAT-AI-Assignment
This file contains all the relatable resources that required to make the given assignment
and for doing all the stuff of work i used GOOGLE COLLAB as a editor for better exprience 
i advice u to simple drag the code from this repository to  code editor to run 


installation instruction
Python: Version 3.7 or later.
pip: Ensure pip is installed for managing Python packages.
Steps to Set Up the Environment
Clone the YOLOv5 Repository
Open your terminal and run the following commands:

git clone https://github.com/ultralytics/yolov5.git
cd yolov5
Install Required Libraries
Install the necessary Python packages using pip:

pip install torch torchvision ultralytics matplotlib
Download the YOLOv5 Pre-Trained Model
Download the yolov5s.pt model file from the YOLOv5 Releases.

Run the following command to verify YOLOv5 setup:

python detect.py --source data/images/bus.jpg --weights yolov5s.pt --save-txt
