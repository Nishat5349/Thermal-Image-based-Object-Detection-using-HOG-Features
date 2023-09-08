# Thermal-Image-based-Object-Detection-using-HOG-Features
It is a Thermal Image-based Object Detection Project. Here specifically I detected Bat at nighttime. A well known machine learning technique, Support Vector Machine (SVM) is implemented here. Here at first I extracted the HOG features. The HOG descriptor is extracted from the testing dataset images by segmenting the input images into small cells, computing the gradient orientations and magnitudes in each cell, and then averaging these values to build a histogram of gradient orientations.

![image](https://github.com/Nishat5349/Thermal-Image-based-Object-Detection-using-HOG-Features/assets/72455268/55fc2d32-c2dd-41e0-abb4-268a6f951f24)

The working Procedure is depicted below:

![image](https://github.com/Nishat5349/Thermal-Image-based-Object-Detection-using-HOG-Features/assets/72455268/6ecfef94-370a-4452-befc-afea3cc3e425)

It performs well on our dataset with 95.56% accuracy, which is better than any other techniques mentioned above. But it cannot localize the object. It just tells whether it is a bat image or not with confidence (%). Moreover, SVM cannot resolve multi-class problem and it cannot detect bats or other type of birds together in a single image. 
Result obtained from SVM:

![image](https://github.com/Nishat5349/Thermal-Image-based-Object-Detection-using-HOG-Features/assets/72455268/206d66d0-8a27-4950-bef7-8f394297372d)

DATASETS WILL BE UPLOADED SOON...
