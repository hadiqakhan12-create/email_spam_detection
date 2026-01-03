Email Spam Detection using Machine Learning
This repository contains my Task 1 project for my Data Science Internship. The project uses Machine Learning to identify whether an email is "Spam" or "Ham" (Legitimate) based on statistical features.

📌 Project Concept
In this project, I used the Spambase Dataset, which represents emails not as raw text, but as a collection of numerical data. These features describe the frequency of specific words (like "money", "free", or "offer") and characters (like "!" or "$").

🛠️ Implementation Steps
I have organized the Jupyter Notebook into clear, modular steps:

Data Loading: Importing the CSV file into a Pandas DataFrame.

Exploratory Data Analysis (EDA): Checking the balance between spam and ham messages.

Data Splitting: Using a train-test split to ensure the model can generalize to new emails.

Model Selection: Implementing the Random Forest Classifier—an ensemble learning method.

Evaluation: Visualizing results through a Confusion Matrix and Accuracy Score.

📊 Technical Stack
Environment: Anaconda & Jupyter Notebook

Language: Python

Key Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn

📈 Model Results
The Random Forest model performed exceptionally well on this dataset:

Accuracy: [Insert your Accuracy, e.g., 95.8%]

Robustness: The model effectively identifies patterns in word frequencies to distinguish spam.

📂 Project Structure
spambase_csv.csv: The processed email dataset.

Spam_Detection.ipynb: The complete Python code with step-by-step documentation.

README.md: Project description and documentation.
