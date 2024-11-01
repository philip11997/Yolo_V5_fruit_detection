# YOLOv5 model

# Train a YOLOv5 model to detect Fruit in pictures. I was working on a fruit detect project by using Yolo V5 models. I tried to test on the image, then I tested on live video by using my webcam. 

The dataset is structured in the following manner:

```
├── data.yaml
├── README.dataset.txt
├── README.roboflow.txt
├── test
│   ├── images
│   └── labels
├── train
│   ├── images
│   └── labels
└── valid
    ├── images
    └── labels

```

### The Dataset YAML File

The dataset YAML (`data.yaml`) file containing the path to the training and validation images and labels is already provided. This file will also contain the class names from the dataset.

The dataset contains 3 classes: **'apple', 'banana', 'orange'**.

The following block shows the contents of the `data.yaml` file.

![image](https://github.com/user-attachments/assets/9389b4ad-8f7a-421c-a208-f3f8c79e39b4)
