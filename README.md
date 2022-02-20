# Brain-Tumor-Detection

## HISTORY


### Abstract
A Brain tumor is considered as one of the aggressive diseases, among children and adults. Brain tumors account for 85 to 90 percent of all primary Central Nervous System(CNS) tumors. Every year, around 11,700 people are diagnosed with a brain tumor. The 5-year survival rate for people with a cancerous brain or CNS tumor is approximately 34 percent for men and36 percent for women. Brain Tumors are classified as: Benign Tumor, Malignant Tumor, Pituitary Tumor, etc. Proper treatment, planning, and accurate diagnostics should be implemented to improve the life expectancy of the patients. The best technique to detect brain tumors is Magnetic Resonance Imaging (MRI). A huge amount of image data is generated through the scans. These images are examined by the radiologist. A manual examination can be error-prone due to the level of complexities involved in brain tumors and their properties.
Application of automated classification techniques using Machine Learning(ML) and Artificial Intelligence(AI)has consistently shown higher accuracy than manual classification. Hence, proposing a system performing detection and classification by using Deep Learning Algorithms using Convolution-Neural Network (CNN), Artificial Neural Network (ANN), and Transfer-Learning (TL) would be helpful to doctors all around the world.

### Context
Brain Tumors are complex. There are a lot of abnormalities in the sizes and location of the brain tumor(s). This makes it really difficult for complete understanding of the nature of the tumor. Also, a professional Neurosurgeon is required for MRI analysis. Often times in developing countries the lack of skillful doctors and lack of knowledge about tumors makes it really challenging and time-consuming to generate reports from MRI’. So an automated system on Cloud can solve this problem.

### Definition
To Detect and Classify Brain Tumor using, CNN or ANN; as an asset of Deep Learning and to examine the tumor position(segmentation).


## About the data:
The dataset contains 3 folders: yes, no and pred which contains 3060 Brain MRI Images. This data is then further divided into Training,Testing and Validation Datasets.

Sample Image from YES:

![yes](https://user-images.githubusercontent.com/56751947/154831360-bb8e8c7f-3a18-435c-bfa5-291518df8261.png)

Sample Image from NO:

![no](https://user-images.githubusercontent.com/56751947/154831377-cdf30d6e-c036-46d4-a310-15a2b624a0bb.png)


## Convolutional Neural Network SUMMARY:
![Screenshot 2022-02-19 230723](https://user-images.githubusercontent.com/56751947/154832529-f6205e71-b0a6-4d59-ba86-a9d75bdd8a2b.jpg)


## The Loss and the Accuracy Curves for Training and Validation datasets:

During the training of a machine learning model, the current state of the model at each step of the training algorithm can be evaluated. It can be evaluated on the training dataset to give an idea of how well the model is “learning.” It can also be evaluated on a hold-out validation dataset that is not part of the training dataset. Evaluation on the validation dataset gives an idea of how well the model is “generalizing.”

- `Train Learning Curve`: Learning curve calculated from the training dataset that gives an idea of how well the model is learning.
- `Validation Learning Curve`: Learning curve calculated from a hold-out validation dataset that gives an idea of how well the model is generalizing.

![Screenshot 2022-02-19 230811](https://user-images.githubusercontent.com/56751947/154832672-76c6560c-6ea3-4a25-9a2a-11e559fa11ea.jpg)

A good fit is the goal of the learning algorithm and exists between an overfit and underfit model.
A good fit is identified by a training and validation loss that decreases to a point of stability with a minimal gap between the two final loss values.
The loss of the model will almost always be lower on the training dataset than the validation dataset. This means that we should expect some gap between the train and validation loss learning curves. This gap is referred to as the “generalization gap.”
A plot of learning curves shows a good fit if:
- The plot of training loss decreases to a point of stability.
- The plot of validation loss decreases to a point of stability and has a small gap with the training loss. 


## Few images of how the model is working and predicting on the data:

![Screenshot 2022-02-19 232515](https://user-images.githubusercontent.com/56751947/154832840-be4c869a-9767-49ea-aacb-ab59347dadc3.jpg)

