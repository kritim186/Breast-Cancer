# Breast-Cancer
 The breast cancer dataset is a widely used dataset for binary classification tasks in machine learning and is particularly used to predict whether a tumor is malignant (cancerous) or benign (non-cancerous) based on various features extracted from digitized images of fine needle aspirate (FNA) of breast masses.
 
## Dataset Characteristics:< br / >
Number of Instances (Samples): 569< br / >
Number of Attributes (Features): 33 (including id, diagnosis, and 30 numeric features)< br / >
##Attribute Information:< br / >
id: Unique identifier for each instance.< br / >
diagnosis: The target variable, indicating the diagnosis of the tumor (M = malignant, B = benign).< br / >
Unnamed: 32: Column with missing data, not used in analysis.< br / >
##Numeric Features:< br / >
The dataset includes 30 numeric features, which are computed for each cell nucleus. These features are divided into three groups:< br / >

Mean values (e.g., radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, compactness_mean, concavity_mean, concave points_mean, symmetry_mean, fractal_dimension_mean)< br / >
Standard error values (e.g., radius_se, texture_se, perimeter_se, area_se, smoothness_se, compactness_se, concavity_se, concave points_se, symmetry_se, fractal_dimension_se)< br / >
Worst values (mean of the three largest values) (e.g., radius_worst, texture_worst, perimeter_worst, area_worst, smoothness_worst, compactness_worst, concavity_worst, concave points_worst, symmetry_worst, fractal_dimension_worst)< br / >
##Feature Descriptions:< br / >
Radius: Mean of distances from the center to points on the perimeter.< br / >
Texture: Standard deviation of gray-scale values.< br / >
Perimeter: Perimeter of the cell nucleus.< br / >
Area: Area of the cell nucleus.< br / >
Smoothness: Local variation in radius lengths.< br / >
Compactness: Perimeter² / Area - 1.0.< br / >
Concavity: Severity of concave portions of the contour.< br / >
Concave Points: Number of concave portions of the contour.< br / >
Symmetry: Symmetry of the cell nucleus.< br / >
Fractal Dimension: Coastline approximation - 1.< br / >
##Objective:< br / >
The primary objective is to use these features to build a predictive model that can accurately classify the tumor as malignant or benign based on the given feature set.

This dataset is used for:

Classification Tasks: Predicting the diagnosis (M or B).
Feature Selection: Identifying the most relevant features for the prediction.
Visualization: Understanding the distribution and relationships between different features.
