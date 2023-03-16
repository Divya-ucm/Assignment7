# Assignment7

Name: Divya Pothuru NetworkId:DXP62920

VIDEO-LINK: https://drive.google.com/file/d/1wOX5RwR-jN31p0RnV2ep7Q0qEMA7IJx9/view?usp=share_link

1. Use the use case in the class:
a. Add more Dense layers to the existing code and check how the accuracy changes.
  Apart from orginal code we have added extra dense layers by loading the dataset and by creating the model then hidden layer ane then added output layer...
  <img width="692" alt="image" src="https://user-images.githubusercontent.com/122486644/225525270-0e508dd5-22ef-4f61-a9a2-6295384f7bc7.png">

2. Change the data source to Breast Cancer dataset * available in the source code folder and make required
changes. Report accuracy of the model.
Then we have added the breast cancer dataset then extracting features and labelsthen encoding the label then splitting the data into training and testing dataset and then evaluting the data set.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/122486644/225525517-48917dab-cb21-4616-852f-211cc25b829c.png">

3. Normalize the data before feeding the data to the model and check how the normalization change your
accuracy (code given below).
from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
Breast Cancer dataset is designated to predict if a patient has Malignant (M) or Benign = B cancer

first we have loaded the dataset and then extract the features and labels then encoded the lables and then scale the input features then split the training and test data then print the data


In class programming:
Use Image Classification on the hand written digits data set (mnist)
1. Plot the loss and accuracy for both training data and validation data using the history object in the source
code.
Next we have plotted the model loss and model accuracy with title,xlabel and ylabel and legends function
![image](https://user-images.githubusercontent.com/122486644/225529377-46e3c9f5-dfc4-4413-a0dd-9b9262ae706d.png)
![image](https://user-images.githubusercontent.com/122486644/225529408-fa4b9c0c-4707-4327-bc8c-ebfceabcfc2f.png)

2. Plot one of the images in the test data, and then do inferencing to check what is the prediction of the model
on that single image.
Plotting the single image in the test data and then getting the prediction of the model 
![image](https://user-images.githubusercontent.com/122486644/225529472-67e27d25-bf9a-4c7b-9018-06be13ad0834.png)

3. We had used 2 hidden layers and Relu activation. Try to change the number of hidden layer and the
activation to tanh or sigmoid and see what happens.
 we have changed the hidden layers to tanh and sigmoid to see the output and finding the accuracy
 ![image](https://user-images.githubusercontent.com/122486644/225530231-70c10687-dcae-4e5b-8e1f-8bf42e42669a.png)

4. Run the same code without scaling the images and check the performance?
we have ran the same code to without checking the performance and scaling of the images 
