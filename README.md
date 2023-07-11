# Melanoma-Assignment
**Problem Statement and conceptual understading**: Melanoma is type of skin cancer, develop primarily in the cells (called melanocytes) that produce melanin pigment. Melanoma however can also be developed in eyes, but rarely inside the body.One of the common known reasons for melanoma is prolonged exposure to high amount of UV-radiations, but there are lot more underlying reasons as well ranging from genetic predisposition, epigenetics and many more under investigation. This type of cancer accounts for 75% skin cancer driven deaths. 
**Task at our hand**:  A CNN model is to be built using number of images of Melanoma based cancers (learning data) that can help in designing an algorithm helpful in accurate primary diagnosis of different types of Melanoma (testing data). These type of applications are gaining increased traction from scientific and medical community as it can be of huge help in reducing the manual ambiguity in reading the images and can serve as an empirical tool for primary diagnosis. Images are sourced from International Skin Imaging Collaboration (ISIC). 

**The data set contains the images classified under the following disease categories:**
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

**Project Pipeline**: 
1. Data Reading and understanding
2. Data Set Creation - Train and Test, with images resized to 180 X 180
3. Dataset visualization
4. Model Building and training
5. Choosing the appropriate data augmentation
6. Model training on augmented data
7. Handling class imbalances
8. Model training on rectified class imbalance data
