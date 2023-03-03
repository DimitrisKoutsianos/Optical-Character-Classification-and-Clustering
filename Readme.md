# Optical Character Classification and Clustring Assignment
## M.Sc. in Data Science (Full-Time) AUEB 2022-2023 

This assignment was part of my Practical Data Science Course during the first quarter of the curriculum. 

The first main task was to classify the images that we were given based on the character they pictured, their 
century of origin and their TM number (which is the unique number of the papyrus that these images come from).
To this end I created three models, a SVM classifier, a K-NN classifier and a Histogram Gradient Boosting 
Classifier.

The second main task was to cluster the images based on the character they pictured and their century of origin, 
and selecct the optimum number of clustrs using the normalized mutual information score. To this end we also used
the pre-trained ResNet50 CNN to extract features of the images and reported the comparison between the number of 
clusters found in both cases.

The third and final main task was to perform a clustering per character and select the optimum number of clusters
using the Davies Bouldin criterion.