# Using-Deep-Learning-to-identify-pneumonia
Image Classification applied on a pneumonia dataset using CNN.

Download the dataset from the link below :
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

Follow the ITR CCFE steps below :
(Could be changed later coz of lack of better words at the moment)

> Start by image resizing.\
> Then proceed to training the layers(or rather setting the last layer as false).\
> Create the model object for vgg16 transfer model.\
> Flatten the model.\
> Compile the model.\
> Now we perform data augmentation.\
> Fit the model.

Now to check the model performance on a chosen test image
>Convert the images to array\
>Expand its dimensions to fit our requuired shape.\
>Preprocess this and store it in a variable.\
>Now predict the model on this image data.\
>As a final step check the image class it belongs to and assign it a value for the image it is classified as.

The below images displays the performance losses details of our CNN model : 

![image](https://user-images.githubusercontent.com/22250758/137967282-071c5d51-c533-4988-81fd-42474af8c8e6.png)

The below images displays the performance accuracies details of our CNN model : 

![image](https://user-images.githubusercontent.com/22250758/137967373-0568648e-ac6e-4a4f-bca4-9fb49979a667.png)


# A code snippet to show the final step of the image classification using model.predict

![image](https://user-images.githubusercontent.com/22250758/137967489-654d4354-f973-4b94-bcc1-b3fe51d9c835.png)
