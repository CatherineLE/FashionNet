# FashionNet
Multi-labels Images classification &amp; recommendation model - Tensorflow &amp; Keras


# Requirements
- Google Drive account to read a notebook on Google Colaboratory with GPU activated
- See DeepFashion database website => Category and Attribute Prediction Benchmark => 289 220 images splited into different folders
- Prepared Data into 5 classes and Attributes for each Classes
- Prepared Data into Validation and Train folders
- 5 generated weights file .h5 through these .ipynb files above

# STEPS 
- 1 : download the data in DeepFashion Database
- 2 : prepare the data into classes/attributes folders then into validation and train folders for each attributes
- 3 : execute for each classes the notebook to generate .h5 5 weight files for color, shape, type, pattern, and fabric (matiere)
- 4 : with theses 5 weight files, execute the recommendation model with 2 new images as input to see some recommended clothes

# Results in FashionNet_End.ipynb final file
With these two input images :
- ![image](https://user-images.githubusercontent.com/46371678/101405057-cd64ee00-38d7-11eb-90f4-185e3d536ee5.png)

We have these recommendations:
- ![recommended_img](https://user-images.githubusercontent.com/46371678/101405397-4e23ea00-38d8-11eb-91e4-d469ebbfb05b.png)

# Comments for the Transfer Learning
- Prediction are satisfying for the Shape, Pattern, Color models
- Prediction to reconsider for the Type, Fabric models

# Comments for the Recommendation model
In spite of theses results the recommendation model works pretty well.


source : https://github.com/PlabanM1/FashionNet
