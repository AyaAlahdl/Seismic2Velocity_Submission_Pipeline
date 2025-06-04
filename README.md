# Seismic2Velocity_Submission_Pipeline

This repository houses the submission pipeline developed for the Yale/UNC-CH - Geophysical Waveform Inversion Kaggle competition. The project focuses on leveraging physics-guided machine learning models to address full-waveform inversion (FWI) problems, specifically in the context of subsurface compaction.

## Project Overview

Full-waveform inversion is a powerful seismic imaging technique that aims to reconstruct high-resolution models of subsurface properties (e.g., seismic velocity) by minimizing the misfit between observed and synthetic seismic waveforms. This competition challenged participants to apply advanced computational techniques to improve the accuracy and efficiency of FWI, particularly considering complex geological phenomena like compaction.

My "Seismic2Velocity_Submission_Pipeline" implements a robust and reproducible workflow for:

* **Data Preprocessing:** Handling and preparing raw seismic waveform data and associated metadata. This includes routines for reading training data files, organizing 10,000 training samples (10 x 2 x 500 data-vel pairs), and scaling seismic data as a function of time.
* **Physics-Guided Machine Learning Model Integration:** Incorporating and applying the developed machine learning models designed to solve the FWI problem with a focus on compaction effects. The pipeline processes velocity maps and seismic data, including functions to plot and extract information from both.
* **Velocity Model Generation:** Producing high-resolution subsurface velocity models from the inverted waveforms. The code includes functionalities to analyze velocity maps, such as calculating average, standard deviation, min, max, median velocities, and Mean Absolute Error (MAE) from median values.
* **Submission Formatting:** Ensuring outputs conform to the Kaggle competition's specific submission requirements. The notebook includes steps for generating the final submission file.

## Key Contributions & Technologies

* **Full-Waveform Inversion (FWI):** Direct application and optimization of FWI principles.
* **Physics-Guided Machine Learning:** Development and integration of models that incorporate geophysical principles to enhance inversion accuracy and stability.
* **Seismic Data Processing:** Techniques for handling and interpreting complex seismic datasets, including visualization functions for seismic data and waveforms at source locations.
* **Reproducible Workflow:** Designed for clear, efficient, and repeatable execution of the inversion process.
* **Kaggle Competition Framework:** Adherence to competition guidelines and submission protocols, including handling the structure of test data with 65,818 datasets.
* **Python Libraries:** Utilizes `numpy`, `matplotlib.pyplot`, `matplotlib.colors`, and `pandas` for data manipulation, analysis, and visualization.

## Why this project?

This project demonstrates my proficiency in applying advanced machine learning techniques to real-world geophysical challenges. It showcases my ability to develop comprehensive data pipelines, integrate complex scientific models, and deliver solutions within a competitive, deadline-driven environment. The focus on physics-guided machine learning highlights an understanding of how to blend data-driven approaches with established scientific knowledge for more accurate and interpretable results.
