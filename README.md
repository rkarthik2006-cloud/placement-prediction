
#first machine learning project

# Student Placement Prediction using Decision Tree

A beginner-friendly Machine Learning project that predicts whether a student is likely to be placed based on academic performance, technical skills, projects, internships, certifications, and DSA score.

##  Project Overview

This project uses a **Decision Tree Classifier** to predict student placement status.

The model takes student-related features as input and predicts:

* `1` → Placed
* `0` → Not Placed

The project was developed and executed using **Google Colab**.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Google Colab
* Decision Tree Classifier

##  Features Used

The model uses the following six features:

| Feature        | Description              |
| -------------- | ------------------------ |
| CGPA           | Student's CGPA           |
| Skills         | Technical skills score   |
| Projects       | Number of projects       |
| Internships    | Number of internships    |
| Certifications | Number of certifications |
| DSA_Score      | DSA performance score    |

`Roll_No` and `Name` are not used for prediction.

## 🤖 Machine Learning Workflow

The project follows these steps:

1. Create the student dataset
2. Convert the dataset into a Pandas DataFrame
3. Select input features (`X`)
4. Select the target variable (`y`)
5. Split the data into training and testing sets
6. Create a Decision Tree Classifier
7. Train the model
8. Generate predictions on test data
9. Calculate model accuracy
10. Predict the placement status of a new student

##  Dataset

The project uses a manually created dataset containing **30 student records**.

The dataset contains information about:

* CGPA
* Skills
* Projects
* Internships
* Certifications
* DSA Score
* Placement status

This dataset is intended for **learning and demonstration purposes**, not as a real-world placement dataset.

## 📈 Model Evaluation

The dataset was divided into:

* **80% training data:** 24 students
* **20% testing data:** 6 students

The Decision Tree model achieved:

**Test Accuracy: 83.33%**

```text
Accuracy = 0.8333
```

On the test set:

```text
Actual values:    [0, 0, 0, 0, 1, 0]
Predicted values: [0, 1, 0, 0, 1, 0]
```

##  New Student Prediction

The model was also tested with a new student:

```text
CGPA: 8.5
Skills: 0
Projects: 0
Internships: 0
Certifications: 0
DSA Score: 22
```

The model predicted:

```text
Prediction: NOT PLACED
```

##  Project Structure

```text
student-placement-prediction/
│
├── student-placement-prediction.ipynb
└── README.md
```

##  Limitations

This project uses a small, manually created dataset of only 30 students. Therefore, the **83.33% accuracy should not be interpreted as real-world placement prediction performance**.

A real-world system would require:

* A much larger dataset
* Real placement data
* Better feature engineering
* Cross-validation
* Multiple model comparisons
* More comprehensive evaluation metrics

##  Learning Outcomes

Through this project, I practiced:

* Creating and handling datasets with Pandas
* Feature and target selection
* Train-test splitting
* Building a Decision Tree Classifier
* Training a Machine Learning model
* Making predictions
* Evaluating model accuracy
* Making predictions for new data

##  Future Improvements

* Use a larger real-world dataset
* Compare Decision Tree with Random Forest and other classifiers
* Add confusion matrix and additional evaluation metrics
* Perform cross-validation
* Build a simple web interface for predictions
* Deploy the trained model

##  Author

**R.Karthik**



