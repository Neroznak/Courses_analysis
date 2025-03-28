# Predicting Course Completion Likelihood

## 1. Project Overview
This project aims to predict whether a student will complete a course based on their behavior during the first two days of the course. The model utilizes data collected from users to determine the likelihood of their successful course completion. This approach enables the segmentation of students and the application of different motivational strategies for those at high risk of dropping out.

## 2. Features
- Predicting course completion likelihood based on student behavior during the early stages of the course.
- Utilizing multiple machine learning algorithms, including Decision Tree, Random Forest, XGBoost, Logistic Regression, and SVM.
- Analyzing student data and creating features and characteristics that may influence course completion.
- Applying the model for student segmentation and developing personalized motivational strategies to reduce dropout rates.

## 3. Technologies and Tools
- **Platforms and Libraries**:
  - Pandas
  - NumPy
  - Scikit-learn (for machine learning)
  - Matplotlib
  - Seaborn
  - tqdm (for tracking progress during computations)
  
## 4. Installation and Setup
1. Clone the repository:
   ```bash
   git clone <URL>
Navigate to the project directory:


cd <project_folder>
Install the required libraries:


pip install -r requirements.txt
Run the scripts to process data and train the model:


python main.py

5. Demo
As a result of the model's work, you can achieve a prediction accuracy of 88%, which allows for effective student segmentation and predicting their behavior. For students with a high probability of not completing the course, additional motivational materials or reminders about the importance of the course can be offered, increasing their chances of finishing the course.
