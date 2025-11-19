📘 README: Medical Insurance Cost Prediction Using Machine Learning
🧠 Project Overview

This project develops a machine learning model that predicts medical insurance charges based on key demographic and lifestyle factors, including:

Age

Sex

Body Mass Index (BMI)

Smoking habits

Geographical region

Previous insurance charges

The model was built and trained using Google Colab, with an emphasis on clean data processing, exploratory data analysis, and model optimisation. The goal of this project is to understand how different variables influence insurance pricing and to demonstrate practical machine learning implementation skills.

📊 Dataset

The project uses the widely known Medical Insurance Dataset, which contains information on over 1,300 individuals.
Key variables include:
| Variable   | Description                                              |
| ---------- | -------------------------------------------------------- |
| `age`      | Age of the individual                                    |
| `sex`      | Male / Female                                            |
| `bmi`      | Body Mass Index                                          |
| `children` | Number of dependents                                     |
| `smoker`   | Yes / No                                                 |
| `region`   | U.S. region (southwest, southeast, northwest, northeast) |
| `charges`  | Medical insurance cost                                   |

🧪 Methods & Approach
1. Data Loading & Problem Definition
The dataset is imported into Google Colab using Pandas, followed by defining the prediction goal (estimating medical insurance charges) and identifying charges as the target variable.
2. Exploratory Data Analysis (EDA)
Initial exploration includes summary statistics, distribution plots of the target variable, histograms and bar charts for feature distributions, and correlation analysis to understand relationships between variables.
3. Data Cleaning & Feature Engineering
This step includes removing unwanted columns, handling missing values, detecting and removing outliers, encoding categorical variables into numeric form, and selecting the most relevant features based on distribution and correlation insights.
4. Model Development
The cleaned dataset is split into training and testing sets. Multiple linear regression and additional machine learning models are trained, with k-fold cross-validation applied to validate performance.
5. Model Evaluation & Selection
Models are compared using metrics such as R², MAE, and RMSE. The best-performing model is selected based on prediction accuracy and generalisation capability.
6. Deployment (Local & Web-Based)
The final model is exported for deployment and integrated into a simple web interface, enabling users to input variables and receive predicted insurance costs.

🚀 How to Run This Project (Google Colab)

Open the notebook in Google Colab

Upload the dataset or mount Google Drive

Install dependencies (if applicable):

!pip install pandas numpy matplotlib seaborn scikit-learn


Run all cells sequentially

Review model performance and prediction outputs

📈 Results

The final trained model demonstrates strong predictive performance and reveals several key insights:

Smoking status is the strongest determinant of high insurance charges

BMI and age also significantly influence cost

Regional differences have moderate but noticeable effects

A summary of model accuracy is included within the notebook.

🎯 Purpose & Learning Outcomes

This project showcases practical skills in:

Data wrangling and preprocessing

Statistical analysis and data visualisation

Building and evaluating machine learning models

Deploying ML workflows in Google Colab

Understanding real-world cost prediction problems

🔧 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib & Seaborn

Google Colab

📬 Contact

If you have questions or would like to collaborate, feel free to connect:

GitHub: https://github.com/LowellMasibo
