# MRI Segmentation
This is a learning project whose aim is to perform segmentation on MR scan images. Since we're in a learning stage, we started wuth classification. For that purpose we are using an Alzheimer's Dataset.<br>
The work uptil now is done on that dataset. We've been applying various models for the classification purpose. <br>
The dataset has 4 unbalanced classes namely `MildDemented`, `ModerateDemented`, `NonDemented` & `VeryMildDemented`. <br>
The best model uptil now is ResNet34 with an accuracy of 75% using the fastai library built upon pytorch. <br>
The models confuses between `NonDemented` & `VeryMildDemented` which seems pretty reasonable.
