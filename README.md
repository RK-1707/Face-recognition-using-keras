# Face-recognition-using-keras
Dataset for the model can be found here:https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset
####
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

train.csv contains two columns, "emotion" and "pixels". The "emotion" column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image. The "pixels" column contains a string surrounded in quotes for each image. The contents of this string a space-separated pixel values in row major order. test.csv contains only the "pixels" column and your task is to predict the emotion column.

The training set consists of 28,709 examples. The public test set used for the leaderboard consists of 3,589 examples. The final test set, which was used to determine the winner of the competition, consists of another 3,589 examples.

####
The graph of loss and accuracy for training and validation set is as below:

![graph](https://user-images.githubusercontent.com/60837429/85926348-8a303900-b8bc-11ea-9e69-52332a1d54dd.png)

####
The normalized confusion matrix is:

![normalized_confusion_matrix](https://user-images.githubusercontent.com/60837429/85926367-a7650780-b8bc-11ea-8ed8-cde1fd933bb3.png)
