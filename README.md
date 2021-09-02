# BRAIN TUMOR DETECTOR

**Building a detection model using a convolutional neural network in Tensorflow & Keras.
Used a brain MRI images data founded on Kaggle.**
---
## About the Data set

**[LINK](https://www.kaggle.com/preetviradiya/brian-tumor-dataset)**

**The Data set contains a folder named BRAIN TUMOR DATA SET along with some CSV files,**
**Main folder contains two folders , one contained cancerous images and one with non cancerous**
<br />
**The Data set contains around 4500 MRI images**

![Screenshot 2021-09-01 215448](https://user-images.githubusercontent.com/81116984/131708425-5a3679e8-b47d-4e38-802d-18d68e2a384b.png)
<br />
<br />
<br />
<br />
![Screenshot 2021-09-01 215512](https://user-images.githubusercontent.com/81116984/131708508-5bf60d35-5266-4cc6-9e9d-221dd6f10be4.png)

## **Data Splitting**
<br />
<br />
**The Data is splitted in the following ways:**
<br />
<br />
**1. 70% of the data for training.**
<br />
**2. 15% of the data for vaidation.**
<br />
**3. 15% of the data for testing.**

___

## **Mobile Net Architecture**

### **Undersatnding the Architecture**
**Each input x (image) has a shape of (224, 224, 3) and is fed into the neural network. And, it goes through the following layers:**
<br />
<br />
<br />
**1.A convolutional layer with 32 filters, with a filter size of (7, 7) and a stride equal to 1**
<br />
<br />
**2.A batch normalization layer to normalize pixel values to speed up computation.**
<br />
<br />
**3.A ReLU activation layer**
<br />
<br />
**4.A Depthwise conviltuion layer , where we apply a single convolutional filter for each input channel**
<br />
<br />
**5.A Zero Padding layer with a pool size of (2, 2).**
<br />
<br />
**6.A flatten layer in order to flatten the 3-dimensional matrix into a one-dimensional vector**
<br />
<br />
**7.A Dense (output unit) fully connected layer with one neuron with a sigmoid activation (since this is a binary classification task).**
<br />
<br />




## **Loss and the Accuracy plots**
![image](https://user-images.githubusercontent.com/81116984/131894523-43eb0e3d-b18b-438d-bcbe-3839ae8fdd0d.png) ![image](https://user-images.githubusercontent.com/81116984/131894611-68bb8ad7-f2fc-4e04-85a4-c3238cc83109.png)




































