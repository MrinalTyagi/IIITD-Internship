# IIITD-Internship
IIITD Internship Task 2

This is a implementation of Task 2 for IIITD Internship.

## Table of contents
* [Technologies](#technologies)
* [Setup](#setup)
	
## Technologies
Project is created with:
* Python 
	
## Setup
This project can be run directly on google colab or jupyter notebook by copying all the files into the folder.
Steps for Jupyter Notebook:
1. Create a virtual environment
2. Install following libraries:
  * pip install keras==2.4.3
  * pip install numpy==1.19.5
  * pip install opencv-python==4.1.2
  * pip install scipy==1.4.1
  * pip install scikit-image==0.16.2
  * pip install matplotlib==3.2.2
  * pip install tensorflow==2.4.1
  * pip install python-mnist
  * pip install Pillow==7.1.2
  * pip install pandas==1.1.5
  * pip install sklearn==0.22.2
  * pip install seaborn==0.11.1
3. Run The .ipynb file within the same folders as other files in the repository to replicate same results.

***Incase of a 2 shape test input please expand the dimensions of the instances to 3 using expand_dims() method with axis=0 arguement***
***To load the model to be used just input the model folder to be loaded into the load_model() function of keras. All models are saved with their respective names as in .ipynb file*
