Car Plates YOLO Dataset

This repository contains labeled data of car plates in YOLO format, with 154 annotated text files and a corresponding classes.txt file.

Files Structure:
Labels:

Each text file in the dataset corresponds to an image and contains bounding box annotations for car plates in YOLO format.

The format is: <object-class> <x_center> <y_center> <width> <height>

<object-class>: The class ID of the object (car plate).
<x_center>: The normalized x-coordinate of the center of the bounding box.
<y_center>: The normalized y-coordinate of the center of the bounding box.
<width>: The normalized width of the bounding box.
<height>: The normalized height of the bounding box.

classes.txt:

This file contains the list of object classes. Each line represents one class in the same order as referenced in the label files.
In this case, the file should contain: car_plate
