# Leaf-Disease-Detection-Using-CNN

OBJECTIVE:
->This Model concerned with a new approach to the development of plant  Diseases detection model by the Convolutional Neural Network.
->	To provide fast and accurate results to know the what plant diseases.

DATASET:
->	Appropriate datasets are required to train over Model.
->	So, I choose PlantVillage dataset from Kaggle.
->	Many times of plant classes are in dataset. 

Task accomplished:

•	Image Preprocessing and Labelling:
  ->Plantvillage dataset class labels are already done
  ->Using Opencv library We can resize over image on our needs.

•	LabelEncoder:
  ->Label Encoding refers to converting the labels into numeric form so as to convert it into the machine-readable form. 
  ->It is an important pre-processing step for the structured dataset in supervised learning.

•	Split Dataset into training and testing:
  ->Dataset split into the 80% for training and 20% for testing.
  ->Using ‘train_test_split’ function of sklearn Library. 

•	Image Augmentation:
  ->Image augmentation artificially creates training images through different ways of processing or combination of multiple processing, such         as random rotation, shifts, shear and flips, etc.
  ->Neural networks need large amount of training data to achieve good performance.

DIFFICULTY DURING WORK
 ->Convert Images to array.
 ->I have difficulty into the load images on the list.
  Solve:  listdir( f “ PATH ")






