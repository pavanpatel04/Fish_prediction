# Fish_prediction
Important
The dataset is provided in the repository as well as a link to download the dataset is provided in the Fish_species_prediction.ipynb file. After downloading the dataset locally in the system , then upload the dataset to the google collab to use it.

Fish_species_prediction
This projects predicts the selected species of fish(Perch ,Bream, Roach, Pike, Smelt, Parkki, Whitefish) based on its length , height , weight. We have used the K Nearest Neighbours classifier from the sklearn library.

Required Libraries:
Numpy
Gradio
Pandas
Seaborn
Matplotlib
Knn classifier
Features
Machine Learning Model: Built using K Nearest Neighbours classifier from the scikit-learn library.
Prediction Interface: A Interface that is built using the Gradio library in python allows for a easy to use userfriendly interface. We can input the different inputs(length, width, height) for the fish and get the name of the fish along with its image.
Dataset
The dataset consists of 160 rows and 7 columns for 7 species of fish.

Perch
Bream
Roach
Pike
Smelt
Parkki
Whitefish
Each sample has 7 features

Weight
Length1
Length2
Length3
Height
Width
Species
Preprocessing
The data is scaled using the Standard Scalar Library

Model Training
The K nearest neighbours model is trained using the 80% of the dataset.
Remaining 20% is used for testing purpose
The model is checked for different parameters such as accuracy score, precision, Recall, f1 score.
Interface
The interface is built using the Gradio library. Input: Enter the Weight, Length, Width Output: The image along with the name of the fish.

