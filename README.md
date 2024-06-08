# HR ANALYSIS
The primary aim of this project is to create a prediction model for employee promotions within an organization using machine learning algorithms. This project offers insights into the factors that influence promotions, helping to ensure a data-driven and fair promotion process.
## Dataset
The dataset used for this project is sourced from Kaggle [https://www.kaggle.com/datasets/shivan118/hranalysis]. It consists of HR data with 50,000 rows and 14 columns. Each year, approximately 5% of the employees are promoted. The objective is to determine whether an employee will be promoted or not based on the given data.
* employee_id: Unique ID for each employee
* department: which department the employee belongs to (Ex: Sales & Marketing, Operations, etc)
* region: which place the person belongs to
* education: Education qualification (Ex: Bachelor's)
* gender: Male or Female
* recruitment_channel: How was he recruited (Ex: sourcing, other)
* no_of_trainings: Range from 1 to 9
* age
* previous_year_rating: Score from 1 to 5
* length_of_service
* KPIs_met: Key performance indicators
* awards_won: either 1 or 0 (Yes or No)
* avg_training_score
finaly we have to predict wheather the employee get promotion(binary classification)
## EDA
Perform exploratory data analysis (EDA) to understand the dataset. Create plots and graphs to visualize the relationships and connections between different features.
## Feature Engineering
* Feature Encoding:use Ordinal Encoding and get_dummies method
* Feature Selection:use chi-square test
## Model creation
I have tested a total of four algorithms on the model to determine the most effective accuracy score
* k-nearest neighbors
* Naive Bayes
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
## Hyperparameter Tunning
I employed RandomizedSearchCV to fine-tune the hyperparameters of the algorithm that yielded the highest accuracy among the ones listed above
