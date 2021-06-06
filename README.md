# Celeb_Update_Project
<img src="https://images.deepai.org/converted-papers/1907.10202/fig/suppl_Fig8_4.jpg">

# Dataset Column's Information

<img src="https://www.researchgate.net/publication/327029519/figure/tbl1/AS:667628372766726@1536186416689/List-of-the-40-face-attributes-provided-with-the-CelebA-database.png">

# Context

A popular component of computer vision and deep learning revolves around identifying faces for various applications from logging into your phone with your face or searching through surveillance images for a particular suspect. This dataset is great for training and testing models for face detection, particularly for recognising facial attributes such as finding people with brown hair, are smiling, or wearing glasses. Images cover large pose variations, background clutter, diverse people, supported by a large quantity of images and rich annotations. This data was originally collected by researchers at MMLAB, The Chinese University of Hong Kong (specific reference in Acknowledgment section).

# Content

Overall

1. 202,599 number of face images of various celebrities
2. 10,177 unique identities, but names of identities are not given
3. 40 binary attribute annotations per image
4. 5 landmark locations


# Data Files

1. imgalignceleba.zip: All the face images, cropped and aligned
2. listevalpartition.csv: Recommended partitioning of images into training, validation, testing sets. Images 1-162770 are training, 162771-182637 are validation, 182638-202599 are testing
3. listbboxceleba.csv: Bounding box information for each image. "x1" and "y1" represent the upper left point coordinate of bounding box. "width" and "height" represent the width and height of bounding box
4. listlandmarksalign_celeba.csv: Image landmarks and their respective coordinates. There are 5 landmarks: left eye, right eye, nose, left mouth, right mouth

# Source of the dataset is as below:-
https://www.kaggle.com/jessicali9530/celeba-dataset


# Acknowledgements

Original data and banner image source came from http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
As mentioned on the website, the CelebA dataset is available for non-commercial research purposes only. For specifics please refer to the website.

The creators of this dataset wrote the following paper employing CelebA for face detection:

S. Yang, P. Luo, C. C. Loy, and X. Tang, "From Facial Parts Responses to Face Detection: A Deep Learning Approach", in IEEE International Conference on Computer Vision (ICCV), 2015
