# Skin-Cancer-Detection

In this Project, I have deployed 6 classification algorithms to classify whether a skin cancer is malignant or benign. The dataset was obtained from https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign.  

As the dataset was already distributed between training and testing data, I just had to import the dataset and merge the datasets of malignant and benign. Below, we can see the balanced data between benign and malignant. There were 2637 number of training data and 660 testing data. 

![ad7014a8-0652-48c5-a936-1027ac472bd7](https://user-images.githubusercontent.com/49121645/210022333-9558dd77-8774-4b85-84e9-1a5bd5883be7.png)

Now I have implemented few algorithms to classify the skin cancer. 

1	Random Forest classifier:	83.333333
![image](https://user-images.githubusercontent.com/49121645/210022657-34f0588b-1711-40b7-8479-deb657f39e62.png)

2	Logistic Regression: 78.636364
![image](https://user-images.githubusercontent.com/49121645/210022668-9ee53d72-fef3-4a31-94d4-1e1b0a0f430c.png)

3	Decision Tree: 76.818182
![image](https://user-images.githubusercontent.com/49121645/210022673-d6663ef9-c894-400f-a3aa-b2aa4a29a424.png)

4	Naive Bayes: 70.151515
![image](https://user-images.githubusercontent.com/49121645/210022681-01dddd91-26d2-4f4e-afda-45e28d38044c.png)

5	ResNet50: 67.812502
![image](https://user-images.githubusercontent.com/49121645/210022686-30448a71-afa9-45cb-95bb-eb4cdec85b9c.png)

6	VGG16: 82.343751
![image](https://user-images.githubusercontent.com/49121645/210022692-a48adf9d-ab9a-45dc-adc8-9bbd7867aa5a.png)

Out of all the six models’ random forest classifier was able to get the best accuracy, but the VGG16 model would have gotten a better accuracy if it had gotten a little more epochs to learn. Even, ResNet50 could have achieved better accuracy if it had been trained on more epochs. Other models could have gotten better accuracy on different hyperparameters.
