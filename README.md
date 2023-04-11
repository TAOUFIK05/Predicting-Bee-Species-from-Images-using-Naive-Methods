# Predicting-Bee-Species-from-Images-using-Naive-Methods 

<p align="center">
    <img src="https://user-images.githubusercontent.com/48359677/231091776-73c4ca75-1cf1-4acc-837b-cdad2c414e09.PNG"/>
</p>

# Predicting-Bee-Species-from-Images-using-Naive-Methods
Bee identification from images is a challenging task, yet it has significant implications for researchers who rely on field data collection. Can a machine accurately identify the species of a bee from an image? In this project, we aim to answer this question by utilizing the Python image library Pillow to load and manipulate image data. Our goal is to build a model that can effectively distinguish between honey bees and bumble bees based on an image of these insects. This project is part of a series that focuses on working with image data, developing classifiers using traditional methods, and utilizing deep learning techniques for computer vision.

<p>
Besides the honey that some produce, the pollination of flowers and plants is essential to our food system. They also do a nice job controlling other pesky insects in the area.  What’s interesting is that I never really stopped to think about the differences in the bees that were buzzing around the roses.
</p>
1.Honey bees

    - Honey bees are generally tan and yellow and have a smooth appearance
    * Another major difference is that honey bees can sting only once as their stinger is barbed and comes out after stinging

2.Bumble bees

    - Bumblebees are black and fuzzy with either yellow or orange markings
    * Bumblebees are also generally much larger than honey bees
    + Also, the bumblebee has a smooth stinger and can sting multiple times


# Libraries

First, we need to import the Python libraries with which we will work.

Import the class Image from the library PIL.
Import the function train_test_split from the model_selection module of sklearn.
Import the function SVC from the svm module of sklearn. This is the model we'll use.
Import the function accuracy_score from the metrics module of sklearn. This is the metric we'll use.
