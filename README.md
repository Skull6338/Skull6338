INTRODUCTION:
Humans can identify patterns and objects, such as a clock, a chair, a dog, or a cat. However, for a computational model, pattern analysis is a considerable challenge.
Using artificial intelligence (AI) makes it possible for computer systems to perform pattern recognition. However, it is necessary to develop models capable of learning.
Through these models, it is possible to achieve methods that align with how the human brain performs the analysis.
Convolutional neural networks (CNNs) have made pattern recognition in images feasible. 
When considering an image, the proximity of the pixels has a strong correlation, and the CNNs specifically use this relationship.
Nearby pixels have a higher probability of being related than pixels further apart.
The evolution of graphics processing units (GPUs) and the availability of libraries, such as TensorFlow (TF) and Keras, have substantially facilitated the development of CNNs. 
The evolution of graphics processing units (GPUs) and the availability of libraries, such as TensorFlow (TF) and Keras, have substantially facilitated the development of CNNs.
Therefore, the main objective of this work was the development of a graphical user interface (GUI) that allows any user without previous knowledge in the area of DL, giving the capability to develop PMs based on CNNs with a no-code approach that follows Matlab’s Classification Learner Application concept.

 MATERIALS AND METHODS:
The data to train the model was collected from kaggle.
Where we collected close to 1600 images.
SUBJECT: 
Classifying different types of soils to predict what best action can be taken to retain its fertility 
DATA PREPROCESSING: 
Customized resize function using the pillow library. 
This function is used to resize all the input images to a standard size. In this case 128x128.
Data augmentation using transforms of the torch library. 
DATASET: 
It is a data set consisting of four types of soils.
i.Alluvial 
ii.Black 
iii Clay
iv.Red
DEEP  LEARNING: 
Convolutional neural networks with custom defined helper functions. 
DIAGNOSTIC PERRFORMANCE: 
Evaluated model using:
i.Heat maps.
ii.Confusion matrix.
iii.Accuracy score. 
iv.Matplotlib charts.
CODE REFRENCES:
i.Codemy.com
ii.Kaggle.com
iii.Stackoverflow.com
RESSULTS:
The model showed highest accuracy of 98% and average accuracy of 95%.
