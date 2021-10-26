# Birds Classification
##### Dorin & Noa

Final project for class.

In order to perform birds classification, we compared 3 classifiers with improvements.
Our classifaires were written in **kaggle notebooks**.

#### Databases we used:
Our database contains about 43622 images for train, 1500 for the test, and another 1500 for the validation.
There are about 3 columns, which contain the paths, annotations - each bird is classified into a particular species, and where the image is classified.
An example of two images from the database can be seen in the picture.

![image](https://user-images.githubusercontent.com/58748407/138856566-391d869d-48db-471e-817d-4512366122fb.png)

#### Models:
**Note- In order to open the notebooks click on the link, then choose 'copy my edit' button (on the top right side of the page).**
- https://www.kaggle.com/noaelishmereni/bird-classification-first-notebook
- https://www.kaggle.com/dorindomin/bird-classification-second-notebook
- https://www.kaggle.com/dorindomin/bird-classification-third-notebook

##### We also included an [Hebrew report](https://github.com/DorinDomin/Practical-topics-in-Machine-Learning-/blob/c827c19884ac61ca84f4fd4f235f0838c5c47388/finalProjectReport.pdf)

#### Conclusions:
- The first model in the experiment is best suited for forecasting with high success rates for our data.
- Unsurprisingly, cnn networks as we have used, give high success rates to our image classification problem.
- Data augmetion is an important part of a process like ours since as part of the data review we did it helps
overcoming several problems including the ability to learn from the images themselves.
- There is an imbalance in terms of the ratio of male images to female images. About 80% are pictures of a male and the rest of a female. This fact is important because males are typical in a wider range of colors compared to females birds. That is, images of males and females can look completely different and affect the learning process and capabilities of the model.
- In case of a limited amount of training samples, it is possible to reuse the weights of the pre-trained model on another data, in our model.
- A pre-trained model (transfer learning) is an important component in solving our problem (since it is included in every model we have tried).
- Improving the architecture of the network by adding new layers in the model we added to it, makes the model more accurate in classifying bird species.
-Increasing the number of epochs can help improve accuracy.
- Standard deviation between pixels can be used as a way to identify defective images (a novelty for us).


![image](https://user-images.githubusercontent.com/58748407/138858363-8355dd51-eecd-4a2d-bbf1-8fd67ea5d819.png)
