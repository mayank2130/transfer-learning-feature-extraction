# transfer-learning-feature-extraction


I use transfer learning feature extraction method to classify images of dogs and cats.

VGG16 the pre-trained model is being used here. 

Feature Extraction: The convoltional layers get frozen and the dense layers of the pre-trained model gets replaced by ours or the new dense layers.

Here, when i trained the model it achived an accuracy of 93%.

Although, if you try the other method of transfer learning i.e., fine tuning it appears to achieve even a higher accuracy on the same pre-trained model of about 95%.

It's big dataset (1 Gigabyte) for a normal CPU or system with a GPU so it might take a bit longer to train.
