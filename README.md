# Employee Salary Prediction

## Overview

This project aims to predict employee salaries using linear regression. The prediction model is developed with both Scikit-Learn and AWS SageMaker, leveraging data analysis and visualization techniques to understand and enhance the model's performance.

## Project Details

### Data Analysis and Visualization

- **Libraries Used:** Seaborn, Pandas
- **Visualizations:**
  - **Histograms:** To visualize the distribution of features.
  - **Pairplots:** To examine relationships between features and target variables.
  - **Regression Plot (Regplot):** To understand the linear relationship between features and salary.
  - **Correlation Matrix Heatmap:** To visualize correlations between different features.

### Data Preparation

- **Libraries Used:** Scikit-Learn
- **Tasks:**
  - Created training and testing datasets.
  - Split the data for model evaluation.

### Model Training

- **Libraries Used:** Scikit-Learn, AWS SageMaker
- **Models:**
  - **Linear Regression (Scikit-Learn):** Trained a linear regression model using the Scikit-Learn library.
  - **AWS Linear Learner Algorithm:** Utilized AWS SageMaker's Linear Learner algorithm for training the model.

### Model Evaluation

- **Libraries Used:** Matplotlib
- **Tasks:**
  - Evaluated the performance of the trained model using visualization techniques to understand model accuracy and potential improvements.

### Model Deployment and Testing

- **Tasks:**
  - Deployed the trained model and tested its performance on new data.

## Technologies Used

- **Python 3**
- **Scikit-Learn:** For model training and dataset creation.
- **Numpy:** For numerical operations.
- **Pandas:** For data manipulation and analysis.
- **Matplotlib:** For plotting and visualization.
- **Seaborn:** For advanced data visualization.
- **AWS SageMaker:** For model training and deployment.

## Data analysis & visualization output

| ![Histogram](/images/pandas-histogram.png)|
|:--:| 
| *Histogram showing distribution of salary and years of experience in the data set* |

| ![Pairplot](/images/seaborn-pairplot.png)|
|:--:| 
| *Pairplot showing relation between each pair of variable in the dataset* |

| ![Seaborn data correlation](/images/seaborn-data-correlation-matrix.png)|
|:--:| 
| *Matrix showing 98% correlation between salary and years of experience* |

| ![Seaborn Scatterplot](/images/seaborn-linear-regression-scatterplot.png)|
|:--:| 
| *Seaborn scatterplot* |

| ![scikit-learn Scatterplot](/images/scikit-learn-linear-regression-scatterplot.png)|
|:--:| 
| *Scikit Learn Scatterplot* |

| ![AWS sagemaker scatterplot](/images/aws-sagemaker-linear-regression-scatterplot.png)|
|:--:| 
| *AWS SageMaker scatterplot result based on 20% data* |


## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/prerna909/employee-salary-prediction.git
