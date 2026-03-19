What is this project about❓
-----------------------------
This project focuses on building an object detection model capable of identifying cars in images using YOLOv8.
The model learns to locate cars by predicting bounding boxes around them.

What problem does this project solve❓
------------------------------------------
This project automates that process by training a deep learning model to:
detect cars
draw bounding boxes around them
predict their locations in new images

What dataset is used❓
-----------------------
The project uses a car object detection dataset that contains:
training images
bounding box annotations stored in a CSV file
Each annotation includes:
image name
xmin,ymin,xmax,ymax
These values represent the bounding box coordinates.

Why did we convert the CSV annotations❓
-----------------------------------------------
YOLO models require annotations in a specific text format

Dataset used in this project:
-------------------------------
https://www.kaggle.com/datasets/sshikamaru/car-object-detection

You can view and run the notebook on Kaggle:
---------------------------------------------
https://www.kaggle.com/code/bassammoustafa/car-object-detection
