# Model_Zoo_ER_Project
In this Repository, I have attempted to use PyTorch instead of Keras, which we(our group) have used in our BCS Summer Project FER(Facial Emotion Recognition) 2020. The original project is about identifying the six/seven basic emotions of Humans. We have used Jaffe, CK+ dataset, and Keras library to train the model. In my code, the preprocessing remains the same, which includes cropping, rotating, normalizing, and downsampling. Then I have come up with a different data augmentation technique and used the PyTorch library instead of Keras to define and train the model.
The accuracy on the 10-fold cross-validation set for the Jaffe dataset came out to be **95.45** and for the CK+ dataset came out to be **90.90**. In the orginal project accuracies came out to be **93.46** for Jaffe dataset and **90.54** for CK+ dataset.
Also our work for the FER project can be viewed at the following link.
https://github.com/pranay172/FER_brain_and_cognitive_society
