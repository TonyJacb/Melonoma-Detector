# Melonoma-Detector
As part of my coursework, I developed a binary classification model that differentiates between malign and benign melanoma. To put this into practical use, I converted into a tflite model to be deployed onto a raspberry pi for practicality.

## Dataset
The dataset used is the [Kaggle Skin Cancer Dataset](https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign)

## Result
![Confusion Matrix](https://github.com/TonyJacb/Melonoma-Detector/blob/main/conf_matrix.png)

To interpret this confusion matrix, benign is set to 0 while malign is set to 1 (as one can see from the notebook) <br>
With this key, we can decipher that it has 41% chance of detecting both benign and malign melanoma in correspondence with the ground truth. <br>
A 3.6% chance of detecting a malign melonam as benign and 13.18% chance of detecting a benign melonama as malign. <br>
<br>
With respect to medical standards, having a low FN score is very essential as the device shouldn't fail to acknowledge fatality.

## Hardware Construction
To support the development of the product, a Fusion 360 Sketch was also made to visualise the placements of the different components such as <br>
battery pack, <br>
Raspberry Pi, <br>
and the camera housing <br>
To view the sketch, visit [here](https://vitstudent1999.autodesk360.com/g/shares/SH919a0QTf3c32634dcf5523a9fcb74003ce) <br>
![Sketch](https://github.com/TonyJacb/Melonoma-Detector/blob/main/MedTech Project_snapshot.png)
