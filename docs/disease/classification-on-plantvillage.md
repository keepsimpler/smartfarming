# Disease classification on PlantVillage

In this chapter, we will design a CNN to perform the plant disease classification task on the PlantVillage dataset. This includes several steps, which are outlined below:

1. Explore and preprocess the PlantVillage dataset
2. Design an isotropic CNN architecture
3. Train the CNN on the PlantVillage dataset
4. Analyze accuracy of the CNN model from the angle of hierarchical confusion matrix

## the PlantVillage dataset

The PlantVillage dataset is a collection of **54,305** images of **14** different plant species, belonging to **38** classes, 12 of which are healthy, 26 of which are diseased.

The dataset was created by the Penn State College of Agricultural Sciences and the International Institute of Tropical Agriculture as a resource for research and development of computer vision-based plant disease detection systems.
The images in the dataset were collected from various sources, including research institutions and citizen scientists, and represent a wide variety of plant species and disease types.

The plants include fruits such as apple, blueberry, cherry, grape, orange, peach, raspberry, squash, strawberry and crops such as corn, soybean and vegetables such as pepper bell, potato, tomato. Each plant is in healthy status or in disease such as scab, rot, rust, and so on.

The number of images of all the different types of plants are different with each other. Such a skewed distribution of the number of images in a dataset is called imbalanced. A imbalanced dataset is more difficult to train then a balanced dataset.

Last, let us show example images of 38 classes. You could click the button below to show more examples.
