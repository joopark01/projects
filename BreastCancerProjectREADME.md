##Breast Cancer Analysis


#Project Overview
This project was completed as part of academic coursework at Boston University. 
It aims to analyze and model a patient dataset to classify tumors as malignant or benign based on features derived from fine needle aspirate (FNA) biopsy images.
**The dataset was found on Kaggle, and uploaded by Nancy Alward, and initially produced by the University of Wisconsin.**

--
#Dataset Description
| Feature           | Description                                            |
|-------------------|--------------------------------------------------------|
| Radius            | Mean of distances from center to points on perimeter   |
| Texture           | Standard deviation of gray-scale values                 |
| Perimeter         | Perimeter length of the cell nucleus                    |
| Area              | Cell nucleus area                                       |
| Smoothness        | Local variation in radius lengths                       |
| Compactness       | (Perimeter² / Area) - 1.0                              |
| Concavity         | Severity of concave portions of the contour             |
| Concave points    | Number of concave portions of the contour               |
| Symmetry          | Symmetry of the cell nucleus                            |
| Fractal dimension | “Coastline approximation” - 1                          |

--
#Data Preprocessing

These variables were replicated into three categories of datapoints: mean, standard error, and worst values. 
A decision tree utilizing logistic regression was conducted to reduce the number of variables to 33.

For purposes of simplicity, man-power, and time limitations of the project in an academic setting, the decision to drop the "se" or "standard error" variables was made. 

The project contains basic data visualization techniques used, as well as several typical machine learning algorithms used to determine the best model for the dataset, with accuracy score as the key metric to determine the best model.

--
#Analysis and Modeling
- Performed exploratory data analysis (EDA) including histograms, box plots, and correlation heatmaps to understand feature distributions and relationships.  
- Tested several machine learning classifiers including KNN, logistic regression, decision trees, random forests, and neural networks.
- Used accuracy score on a held-out test set as the main evaluation metric.  
- Identified the best-performing model and summarized its performance. 

*(Detailed results, visualizations, and code can be found in the respective notebooks/scripts.)*


