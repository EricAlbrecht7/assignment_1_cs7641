README for Eric Albrecht CS7641 Lab 1: Supervised Learning

Zip file is provided with base working structure. The user needs to do the following:

1. Make sure that Python 3.12.2 is installed.
2. Create new directory for this project. 
3. If needed, here is the directory structure:

project
	src
		eda
			assignment1.ipynb
	data
		airline
			model_outputs
				knn
					classification
				svm
					classification
				nn
					classification
			raw
				train.csv
				test.csv
		waze
			model_outputs
				knn
					classification
				svm
					classification
				nn
					classification
			raw
				waze_app_dataset.csv

Dataset Sources

Waze: https://www.kaggle.com/datasets/raminhuseyn/wase-navigation-app-dataset

Airline: https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction?select=train.csv


				

4. Create a new virtual environment for this project inside the directory, named env. 
5. Copy the project contents into the folder making sure the src, setup, and data folders are present.
6. Activate env and run "pip install -r setup/requirements.txt"
7. Open the assignment1.ipynb file in src/eda.
8. Connect to the environment generated earlier and run the file.
