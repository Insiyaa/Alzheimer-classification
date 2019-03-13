# Alzheimer's Classification
We are using an Alzheimer's Dataset.<br>
The work uptil now is done on that dataset. We've been applying various models for the classification purpose. <br>
The dataset has 4 unbalanced classes namely `MildDemented`, `ModerateDemented`, `NonDemented` & `VeryMildDemented`. <br>
The best model uptil now is ResNet34 with an accuracy of 75% using the fastai library built upon pytorch. The trained weights are saved in `.models/` as `resnet34_unfreezed.pth`. <br>
The models confuses between `NonDemented` & `VeryMildDemented` which seems pretty reasonable. <br>
