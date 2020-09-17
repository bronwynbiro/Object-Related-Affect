# Object-Related-Affect
Note: OpenFace needs to be downloaded to run the final functions from the project
## Instructions
1. Please open the Project.ipynb file in Google Colab
2. Please unzip the dataset.zip file and upload 'annotationsv3.csv' and 'train_cleaned.csv' to your Google Drive
3. Please extract the Training_set_single_face_pics.zip to folder Training_set_single_face_pics and upload the Training_set_single_face_pics folder to your Google Drive.
4. Run the code section by section to see the output. 
5. To run the code in "Examples of images processed and predicted on happiness" section. You need to unzip real_data.zip and upload all the photos in the folder to content folder in Google Colab first. 

## Overview
Many emotion recognition systems rely solely on facial expressions, leaving out important contextual information such as gaze and the objects in the scene. The task of using objects to determine emotion is a challenge as the emotion expected in an image may differ significantly depending on which objects are present, even if the facial expression is the same. Similarly, the same object can lead to different emotions. We intend to resolve this by taking objects, gaze, and Facial Activation Units into account in emotion appraisal. We created a novel dataset by creating a feature for whether a person in an image is looking at cake via the class and coordinates of objects from the COCO dataset, and combined it with Facial Activation Unit data from OpenFace. We experimented with Decision Tree and Random Forest models to both classify happiness and predict the intensity of happiness, and achieved a classification F1 score of 0.97 for the Random Forest classification task, and a MSE of 0.44 for the Random Forest regression task. 

## Paper
View the paper [here](https://drive.google.com/file/d/1SDj80jtlL0Mcsc29Vckv-hToq0krI7Tt/view?usp=sharing)
