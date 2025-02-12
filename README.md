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

# Model Results
![val_batch2_pred](https://github.com/user-attachments/assets/c4136d2b-0973-4ea8-94e4-920c46045e56)
![val_batch1_labels](https://github.com/user-attachments/assets/c702953b-64e7-4657-bf44-80d6f4926984)
![train_batch7741](https://github.com/user-attachments/assets/5b768917-285d-419b-b80f-8398449a46c9)
![results](https://github.com/user-attachments/assets/fd4c4e2a-31c6-44c0-90da-c4f283c8eee3)
![labels_correlogram](https://github.com/user-attachments/assets/3baf03e6-8f32-41de-95b9-61a810d6bede)
![confusion_matrix_normalized](https://github.com/user-attachments/assets/a53ff807-e674-4fb8-a28a-fe28ee4f3d4e)

