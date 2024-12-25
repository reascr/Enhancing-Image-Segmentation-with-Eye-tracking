# Enhancing-Image-Segmentation-with-Eye-tracking

This repository contains code and data used for the final project in the class "Computational Cognitive Science III" at the University of Copenhagen. 

#### Analysis-of-Fixation-Patterns

- ##### Determining-the-dominant-eye.ipynb
  Code to determine the dominant eye of a viewer.
- ##### analysis-of-fixation-patterns.ipynb
  Code to analyse which fixation point (longest duration, first, last, etc.) usually lies on the object.
- ##### one-fixation-point-for-sam.ipynb
  Code to explore whether the fixation point with the longest duration yields better segmentation masks.
  
#### Datasets

This folder contains the eye tracking data (fixation points) extracted from the POET dataset.

- ##### eye_tracking_data.csv
- ##### eye_tracking_data.pkl.zip

#### Data-Preprocessing

- ##### exploring-eye-tracking-data-POET.ipynb
  Code to analyse the eye tracking data of the POET data set and store it as a .csv and .pkl file for further processing.
  

#### SAM

- ##### compare-segmentations-with-ground_truth.ipynb
  Code to calculate the Dice coefficient between segmentation masks generated by passing SAM human fixation points and points generated by Ablation or GradCAM. Addiotnally, performs Wilcoxon signed-rank tests to see whether differences in Dice coefficients between human and model generated points are significant.
