# Distracted-Driver-Detection
Using a Convolutional Neural Network to classify if a driver is attentive or not. Done through Inspirit AI. 
1. Initially used a KNN to make predictions between classifications. Had accuracy of 48.8 percent. Reason was due to random chance
2. Later created a 2 layer CNN to improve the accuracy of the model. This got accuracy up to 60 percent. Model overfitted
3. Learnt about existing models and implemented and trained a VGG16 Model. According to the confusion matrix, has 89 percent accuracy
   

## Understanding our Data
![image](https://github.com/user-attachments/assets/aeb60005-8211-4063-9fa7-fc74af542770)

The graph above summarizes our data effectively. We have a 80-20 split between training and testing data, an ideal split. We also have equal spread between each category so there is equal representation in our data. It is safe to say we can continue with implementing our model. 


## Saliency Graphs
![image](https://github.com/user-attachments/assets/d15b8fd4-e503-49e1-91da-be6859f8b9a8)

The Saliency Graph above tells use what influences the decisions of the model to classify an image as something. In the case of this project, the model uses the position of the hand to classify if the driver is distracted

## Confusion Matrix
![image](https://github.com/user-attachments/assets/935d8fa9-2a58-45c0-a655-b2a98016b7f0)

The Confusion Matrix above shows the accuracy of our model. True positives and true negatives are accurate predictions done by the model. Our model has an 89 percent accuracy rate. We also have less false negatives so our model is safe to implement because the driver does not a false sense of safety.

