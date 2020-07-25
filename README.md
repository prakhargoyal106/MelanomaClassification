# Using CNN for Melanoma Classification

This project is build for binary classification of Melanoma (Skin Cancer) in images of skin lesions. Melanoma is a deadly disease, but if caught early, most melanomas can be cured with minor surgery. Image analysis tools that automate the diagnosis of melanoma will improve dermatologists' diagnostic accuracy. Better detection of melanoma has the opportunity to positively impact millions of people.

## Built Using

* Pytorch


## Data Augmentation Technique

* Remove Hair: In the dataset there were many images with body hair covering the lesion area, this could lead our model to learn false information during training. To avoid this a data augmentation technique- RemoveHair was introduced to remove the hairs from the image

* Microscope: Some of the images in dataset have black areas around the lesion area as if the image was taken from microscope. Using Microscope data augmentation technnique, few more such images were introduced in dataset. This helped increase model accuracy.


## Future Work

* Introduce new machine learning optimization techniques to improve model accuracy
* Add more Data Augmentation strategy for better generalization of model
 
<img src="images/task1_input.png" alt="task1 input" style="width:100px;"/>
