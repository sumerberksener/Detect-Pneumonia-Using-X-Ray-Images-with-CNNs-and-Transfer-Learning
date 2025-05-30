# Detect-Pneumonia-Using-X-Ray-Images-with-CNNs-and-Transfer-Learning
I trained four different models in the project to predict whether a patient has pneumonia or not by looking at their X-ray scans. In the first two of these models I employed simple CNN models and in the last two I employed transfer learning using the `ResNet50V2` pre-trained mode.

The accuracy score achieved by the models were as below:
1. First simple CNN model: achieved an accuracy score of 0.78 on the test set.
2. Second simple CNN model: achieved an accuracy score of 0.82 on the test set. Accuracy was improved due to introducing Dropout layers in the CNN model to tackle the overfitting problem. Moreover, used RandomZoom and RandomRotation layers for data agumentation. 
3. First transfer learning model: achieved an accuracy score of 0.88 on the test set 
4. Second transfer learning model: achieved an accuracy score of 0.89 on the test set. Learning rate was reduced which reduced in achieving a better accuracy with the transfer learning model. 

Our second transer learning model has achieved 0.89 accuracy score on the test set. This could have important use cases in the healthcare industry. Depending on what level of accuracy is required, employing a CNN model such as the one we've developed could greatly reduce the time medical professionals spend analysing the X-ray scans.

The dataset used in this project couldn't be uplaoded to the repository due to its large size, however, it can be obtained using [this link](https://data.mendeley.com/datasets/rscbjbr9sj/2).
