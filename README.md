# Bee Species Identification from Images using Deep learning

<p align="center">
    <img src="https://user-images.githubusercontent.com/48359677/231091776-73c4ca75-1cf1-4acc-837b-cdad2c414e09.PNG"/>
</p>

Bees play a crucial role in our ecosystem by pollinating plants and producing honey. However, different bee species have distinct physical features, making it a challenging task to identify them from images. Honey bees and bumblebees have noticeable differences in appearance, such as color and texture. Additionally, honey bees can only sting once, while bumblebees can sting multiple times due to their smooth stinger. By understanding these differences, we can improve our model's accuracy and ensure reliable bee species identification.

#### 1.Honey bees

    I. Honey bees are generally tan and yellow and have a smooth appearance.
    II. Another major difference is that honey bees can sting only once as their stinger is barbed and comes out after stinging.

#### 2.Bumble bees

    I.  Bumblebees are black and fuzzy with either yellow or orange markings.
    II.  Bumblebees are also generally much larger than honey bees.
    III.  Also, the bumblebee has a smooth stinger and can sting multiple times.

This notebook walks through building a simple deep learning model that can automatically detect honey bees and bumble bees and then loads a pre-trained model for evaluation.

Our project is part of a series that focuses on working with image data and building classifiers using traditional methods and deep learning techniques for computer vision. By accurately identifying bee species from images, we can help researchers collect field data more efficiently and effectively.

# Data

The data is in the Excel file named Honey_Bumble_Bees.xlsx, which contains 2 columns: Image_id and Type.

index: refers to the ID of the bee image.
genus: indicates the type of bee. Type takes the value of 0.0 (Apis or honey bee) or 1.0 (Bombus or bumble bee).

The total size is 1,654 images, with 827 for each type of bee.
