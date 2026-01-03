Email Spam Detection using Random Forest
This project is part of my Data Science Internship (Task 1). It demonstrates a complete machine learning pipeline to classify emails as Spam or Ham (Legitimate) using the Spambase dataset.

📌 Project Overview
The objective of this project is to build an automated system that identifies spam emails based on word and character frequencies. By leveraging the Random Forest Classifier, the model can accurately distinguish between legitimate communications and unsolicited spam.

📊 Dataset Information
I utilized the Spambase Dataset, which includes:

Total Samples: 4,601 emails.

Features: 57 numerical attributes representing word and character frequencies (e.g., "free", "money", "!").

Target: class (1 for Spam, 0 for Ham).

🛠️ Implementation Steps
The project is organized into clear, sequential steps within the Jupyter Notebook:

Environment Setup: Importing pandas, sklearn, and visualization libraries (seaborn, matplotlib).

Data Loading: Reading the spambase_csv.csv file into a DataFrame.

Exploratory Analysis: Inspecting the data structure and checking the balance between Spam (1,813) and Ham (2,788) samples.

Data Preparation: Splitting the data into features (X) and target labels (y), followed by an 80/20 train-test split.

Model Training: Training a Random Forest Classifier with 100 estimators.

Evaluation: Calculating model accuracy and generating a confusion matrix to visualize performance.

💻 Tech Stack
Language: Python

Environment: Anaconda / Jupyter Notebook

Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn

📈 Model Performance
Algorithm: Random Forest Classifier

Accuracy: 95.4%

📂 Repository Structure
email_spam_detection.ipynb: The full Python implementation with step-by-step documentation.

spambase_csv.csv: The dataset used for training and testing.

README.md: Project documentation.
