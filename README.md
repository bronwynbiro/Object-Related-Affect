# Object-Related-Affect
Note: OpenFace needs to be downloaded to run the final functions from the project
## Instructions
1. Please open the Project.ipynb file in Google Colab
2. Please unzip the dataset.zip file and upload 'annotationsv3.csv' and 'train_cleaned.csv' to your Google Drive
3. Please extract the Training_set_single_face_pics.zip to folder Training_set_single_face_pics and upload the Training_set_single_face_pics folder to your Google Drive.
4. Run the code section by section to see the output. 
5. To run the code in "Examples of images processed and predicted on happiness" section. You need to unzip real_data.zip and upload all the photos in the folder to content folder in Google Colab first. 

## Self-evaluation
### Compared to the project proposal, here is a list of things that aren't included in the project:
1. Deep neural network models are not used in our project. Due to small dataset size of 509 photos, a neural network is not considered. 
2. Sub-emotions are not annotated or researched on due to time constraint
3. No food item other than cake is examined due to time constraint. 

### The rest of items mentioned in proposal are fulfilled in the project.

### Here is the list of things that aren't mentioned in the proposal but are included in the project:
1. Photo data are processed and the facial features are extracted
2. A function is developed to check if the person in the photo is looking at the cake
3. Random Forest models and Decision Tree models are used to predict happy emotion and intensity of emotion
4. Besides F1 score, accuracy is also used to measure accuracy of emotion classification models
4. Mean Square Error, Mean Absolute Error, and Root Mean Square Error are used to measure accuracy for regressor models that predict intensity of happy emotion.
