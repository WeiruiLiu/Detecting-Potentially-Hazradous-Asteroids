# Detecting Potentially Hazradous Asteroids
Group Project - Rayna Liu, Zheyue Wang

## Background and Introduction
Asteroids, sometimes called minor planets, are small rocky bodies that orbit the Sun. The currently known asteroid count is 1,113,527. Most asteroids are within the main asteroid belt between Mars and Jupiter, some have more eccentric orbits, and a few pass close to the Earth or enter the atmosphere as meteors.

Scientists continuously monitor asteroids, especially potentially hazardous asteroids, through observatory observation and launching probes. Potentially hazardous asteroids, whose orbit can make close approaches to the Earth and are large enough to cause significant regional damage in the event of an impact.

## Problem Statement
Asteroids are concerned that they will get gravitational disturbances that modify their orbits as they orbit the Sun. Some of them come close to Earth, known as near-Earth objects. Since they are at risk of hitting Earth, it is important to build machine learning models to detect potentially hazardous asteroids that could help spot the danger early and respond to it in time.

## Data Source
Asteroid Dataset [[Source Link]](https://www.kaggle.com/datasets/sakhawat18/asteroid-dataset).
This data is taken from Kaggle. The uploader collected this dataset officially maintained by the Jet Propulsion Laboratory of California Institute of Technology, an organization under NASA. This dataset includes 958,524 unique asteroids, 44 attributes which contain 7 identify attributes, 4 size attributes, 33 orbital attributes, and one target variable (potential hazards asteroid or not).

## Problem Elaboration
* Data Inspection & Wrangling
  * Check duplicate observations
  * Handle missing values
  * convert column data type
* Exploratory Data Analysis
  * Interactive visualization is in [Tableau Public](https://public.tableau.com/app/profile/weirui.liu/viz/DetectingPotentiallyHazardsAsteroid/PHANEOOrbitClass)
* Data Preprocessing
  * Handel identifiers
  * Encode features and target
  * Split train, validation, and test set
  * Normalizing
  * Handle class imbalance
* Models: 
  * Machine Learning Models (7)
    * Random Forest
    * XGBoost
    * Decision Tree
    * Naive Bayes
    * Logitic Regression
    * Support Vector Machine (SVM)
    * K-Nearest Neighbors (KNN)
  * Neural Network
    * Multilayer Perceptron Model
* Results and Analysis
  * Model Comparison
  * Best Model MLP Visualization
* Conclusion and Future Research

# How it Works
1. Read **Final Presentation PPT.pptx**.
2. Check python code click [Github Pages](https://weiruiliu.github.io/Machne-Learning-MLP-Detecting-Potentially-Hazradous-Asteroids/Detecting_Potentially_Hazardous_Asteroids.html).

**If any problem in code, going to Zheyue Wang GitHub click [Here](https://github.com/zheyue/Detecting-Potentially-Hazradous-Asteroids).**



