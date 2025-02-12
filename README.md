# Human-Emotion-Detection-Model-using-YOLOv9
The Human Emotion Detection System revolutionizes traditional emotion analysis methods by leveraging advanced robotics, machine learning, and computer vision to accurately detect and interpret human emotions in real-time.

# Data Set Download
You can download the data set from the link:
https://universe.roboflow.com/facialemotionrecognition/thesis-xjhyc/dataset/2
Downlad the Data Set with YOLOv9 format

# Data Set Changes
Extract the Data Set and follow the format :
DataSet/
├── data.yaml
├── images/
│   ├── train/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── ...
│   └── val/
│       ├── image1.jpg
│       ├── image2.jpg
│       └── ...
│   └── test/
│       ├── image1.jpg
│       ├── image2.jpg
│       └── ...
└── labels/
    ├── train/
    │   ├── image1.txt
    │   ├── image2.txt
    │   └── ...
    └── val/
    |    ├── image1.txt
    |    ├── image2.txt
    └── test/
        ├── image1.txt
        ├── image2.txt

# For yaml File do these changes

train: /content/DataSet_1/train/images
val: /content/DataSet_1/valid/images
test is optional
test: /content/DataSet_1/test/images

nc: 6
names: ['angry', 'fear', 'happy', 'neutral', 'sad', 'surpised']

       
Then create the zip of the folder

# Upload the Data Set
Upload the data to gdrive and the use google collab for Model Training
Set The Notebook settings to T4 GPU
Then follow the code file for Training of Model
Thanks

