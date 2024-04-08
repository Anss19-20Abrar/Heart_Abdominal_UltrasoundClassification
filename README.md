# Heart_Abdominal_UltrasoundClassification
# Medical Imaging Data Science Project

This repository contains the code and data for a data science project focused on medical imaging analysis. The objective of this project is to use machine learning techniques to solve a medical imaging problem using ultrasound images.

## Dataset
The ultrasound images used in this project were collected from the Stanford EchoNet challenge. The dataset consists of two main categories of images:
- **Heart Ultrasounds**: This directory contains a sequence of 218 four-chamber heart ultrasound images of a patient’s heart, each of size 128x128 pixels. The images are split into the following subdirectories:
  - `closed`: Contains 80 images where the Mitral valve appears fully closed, thus clearly splitting LV and LA chambers.
  - `open`: Contains 138 images where the Mitral valve is open or not fully closed.
  - `various`: Contains segmentation masks manually annotated by clinicians, along with a .gif file showing the sequence of images and a .tiff file with the ordered sequence.
   link of data set 
You can find the data set here
https://www.dropbox.com/scl/fo/m7bybibrpwhpdwvyy6434/h?rlkey=n98gkl69vf8i5m4hdjj60ib7d&dl=0'


- **Abdominal Ultrasounds**: This directory contains 925 images of 128x128 pixel abdominal ultrasounds. These images correspond to the training and testing set of the abdominal ultrasound images from the US simulation & segmentation challenge on Kaggle.

## Experiments
The project is divided into three main experiments, each focusing on different aspects of medical imaging analysis using machine learning techniques:

1. **Experiment 1**: Classification of abdominal ultrasounds and heart ultrasounds.
2. **Experiment 2**: Classification of "open" and "closed" heart ultrasounds.
3. **Experiment 3**: Improvement of classification results using advanced techniques such as image augmentation, attention mechanisms, and transfer learning.

## How to Use
1. Clone this repository to your local machine.
2. Download the dataset from the provided Dropbox link and extract it into the `data` directory.
3. Open and run the Jupyter Notebook `Medical_Imaging_Analysis.ipynb` to see the code implementation and results for each experiment.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow, Keras, OpenCV, etc. (See requirements.txt for details)

## Acknowledgments
- The ultrasound images were collected from the Stanford EchoNet challenge (https://aimi.stanford.edu/echonet-dynamic-cardiac-ultrasound).
- Abdominal ultrasound images are from the US simulation & segmentation challenge on Kaggle.

## References
- Provide relevant references to papers, tutorials, or documentation used during the project.

Feel free to explore the code and experiment with different techniques for medical imaging analysis! If you have any questions or feedback, please don't hesitate to reach out.

*Note: This readme file is a template and may need to be customized based on the specific details and outcomes of your project.*
