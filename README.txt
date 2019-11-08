########## CONTENT ##########

This repository contains all the files concerning the Recommender project for the Personalization Theory class IEOR 4571. It has been created by a group of three students, Paul Doan (pqd2001), Bertrand Thia-Thiong-Fat (bt2513), and Jeremy Yao (jy3015).

You will find the following documents:

1- this README file, which outlines the repository contents.

2- a requirement file ('Requirements.txt'), which describe all the packages necessary to run our code.

3- Comparison_models.ipynb: in this notebook we compare our results: 
	- with respect to the dataset sizes,
	- with respect to the algorithms used.

4- Final_code.ipynb: This notebook displays the implementation of our different models for a specific sample of our dataset. A study on different samples can be found in the 'models' folder.

5- 'models' folder: this folder contains 5 folders and one Jupiter notebook:
	- 'Different_dataset_sizes' folder: it contains the study of our different models with respect to the dataset sizes,
	- 'Different_neighborhood_sizes' folder: it contains the study of our user-based models with respect to the neighborhood sizes,
	- 'FitModelALS_Xmovies': saved spark ALS models for different dataset sizes (X movies in the dataset). They can be loaded using the spark function 'ALSModel.load()'.
	- 'Baseline_Model.ipynb': implementation of a two baseline models and comparison. During our study, we chose to use the best one.

6- 'Results' folder: contains the .csv files of the predictions of our user-based models for different dataset sizes and neighborhood sizes.   

7- Final_code.pdf: pdf of our Final_code Jupiter notebook.






