# Skin-Cancer-Detection

In this Project I have deployed 6 classification algorithms to classify wheather a skin cancer is malignant or benign. The dataset was obtained from https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign.  

As the dataset was already distributed between training and testing data, I just had to import the dataset and merge the datasets of malignant and benign. Below we can see the balanced data between benign and malignant. There were 2637 number of trainging data and 660 testing data. 
![ad7014a8-0652-48c5-a936-1027ac472bd7](https://user-images.githubusercontent.com/49121645/210022333-9558dd77-8774-4b85-84e9-1a5bd5883be7.png)

Now I have implememnted few algorithms to classsify the skin cancer. 
1	Random Forest classifier:	83.333333
2	Logistic Regression: 78.636364
3	Decision Tree: 76.818182
4	Naive Bayes: 70.151515
5	ResNet50: 67.812502
6	VGG16: 82.343751

Out of all the six models’ random forest classifier was able to get the best accuracy but the VGG16 model would have gotten a better accuracy if it would have gotten a little more epochs to learn. Even ResNet50 could have achieved better accuracy if it would have been trained on more epochs. Other models could have gotten better accuracy on different hyper parameters.
