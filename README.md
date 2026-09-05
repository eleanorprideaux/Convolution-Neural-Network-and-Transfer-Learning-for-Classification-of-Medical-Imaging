# Convolution-Neural-Network-and-Transfer-Learning-for-Classification-of-Medical-Imaging
Comparing a custom CNN with a ResNet18 transfer learning model for classifying 3,064 brain tumour MRI scans into glioma, meningioma, and pituitary tumour categories, evaluating the effectiveness of deep learning approaches for medical image classification.

## Models Used

### Convolutional Neural Network (CNN)

A custom CNN was developed and trained to learn relevant features directly from the MRI images and classify them into the three tumour categories.

### ResNet18 Transfer Learning

A pre-trained ResNet18 model was adapted using transfer learning for the brain tumour classification task. This approach uses features learned from a large image dataset and fine-tunes the model for MRI classification.


## Results

The CNN achieved an overall accuracy of 88.8%, with ROC-AUC values above 0.958 for all tumour classes. It performed particularly well in identifying pituitary tumours, while some confusion remained between gliomas and meningiomas. The ResNet18 transfer learning model achieved a higher overall accuracy of 96.3%, correctly classifying 93.10% of meningiomas and 100% of pituitary tumours. It also significantly reduced the misclassification of meningiomas as gliomas, demonstrating improved performance compared to the CNN. The full report on the results can be found here, [Medical-Imaging.pdf](https://github.com/user-attachments/files/31867239/Medical-Imaging.pdf)



