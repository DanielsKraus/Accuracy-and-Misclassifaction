# Project Overview

## Accuracy-and-Misclassifaction
Day and night image classifier using 100 day images and 100 night images

## Project Instructions
Overview
Using Anaconda consists of the following:
Install miniconda on your computer, by selecting the latest Python version for your operating system. If you already have conda or miniconda installed, you should be able to skip this step and move on to step 2.
Create and activate * a new conda environment.
* Each time you wish to work on any exercises, activate your conda environment!


1. Installation
    Install latest miniconda

2. Create and Activate the Environment
  ```	
    conda install git
  ```	
1. Clone the repository and navigate to the downloaded folder.
	
	```	
    git clone https://github.com/udacity/CVND_Exercises.git
    cd CVND_Exercises/1_1_Image_Representation
    jupyter notebook 
		
	```
 2. Create an enviroment 
  ```
  conda create --name cv-nd python=3.6
  activate cv-nd
  ```
  3. Install required pytorch for deep learning
  ```
  conda install pytorch-cpu -c pytorch
  pip install torchvision
  ```
  4. Pip install the requirements
  ```
  pip install -r requirements.txt
  ```
Image dataset 
http://cs.uky.edu/~jacobs/datasets/amos/
