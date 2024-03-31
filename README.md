
# Cluster Varieties of Wheat


**Table of Contents**
1. [Introduction](#introduction)
2. [Background](#background)
3. [Objectives](#objectives)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Technologies Used](#technologies-used)
7. [Tech Stack](#tech-stack)


## Introduction
This project focuses on the classification of wheat seeds into three different varieties: Kama, Rosa, and Canadian. Utilizing high-quality visualization techniques through soft X-ray imaging, we analyze the internal structure of wheat kernels to develop a robust machine learning model. The dataset comprises 70 elements from each wheat variety, selected randomly for this study. The aim is to employ clustering techniques to accurately classify the wheat seeds, thereby contributing to the efficiency and precision of agricultural practices.

## Background
The wheat grains used in this experiment were obtained from experimental fields and analyzed at the Institute of Agrophysics of the Polish Academy of Sciences in Lublin. The non-destructive nature of soft X-ray imaging, along with its cost-effectiveness compared to scanning microscopy or laser technology, makes it an ideal choice for this research.

## Objectives
- To develop a machine learning algorithm capable of classifying wheat seeds into their respective varieties with high accuracy.
- To enhance model performance through effective data cleaning techniques and optimization of clustering methods.

## Methodology
- **Data Visualization and Preprocessing:** Applied One Hot encoding and the drop method to clean the data, resulting in 100% clean data.
- **Machine Learning Techniques Used:**
  - **KMeans Clustering:** Initial attempts at seed classification.
  - **Principal Component Analysis (PCA):** Employed to reduce dimensionality and improve clustering accuracy.
- **Performance Improvement:** Addressed initial low accuracy issues by applying KMeans with higher dimensions, which increased the clustering precision by 20%.

## Results
The machine learning model developed during this project achieved an 88% accuracy rate in grouping the wheat seeds into their correct varieties. This significant level of precision demonstrates the potential of clustering techniques in agricultural classification tasks.

## Technologies Used
- **Python:** For implementing the machine learning model and data processing.
- **Scikit-learn:** Utilized for KMeans clustering and PCA.
- **Pandas:** For data manipulation and cleaning.
- **Matplotlib/Seaborn:** For data visualization.

## Tech Stack
The project leverages a comprehensive tech stack for data processing, analysis, and machine learning model development:
- **Programming Language:** Python
- **Machine Learning Library:** Scikit-learn
- **Data Manipulation:** Pandas
- **Data Visualization:** Matplotlib, Seaborn
- **Development Tools:** Jupyter Notebooks for interactive development and testing



This enhanced README now includes a detailed Table of Contents and a Tech Stack section, offering a clear overview and technical insight into your project. Adjust the "How to Use" section with specific setup and execution instructions relevant to your repository.
