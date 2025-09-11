Simple Iris Flower Classification Project
A friendly and straightforward machine learning project for the Microsoft Club recruitment task. This project builds a model to classify species of Iris flowers based on their petal and sepal measurements.
About This Task
This project is designed to demonstrate a fundamental understanding of the machine learning pipeline, from loading data to evaluating a model. The goal is to keep it simple, clean, and easy to understand for anyone new to ML!
Problem Statement
The main goal is to build a model that can correctly predict the species of an Iris flower (setosa, versicolor, or virginica) given four of its physical measurements:
Sepal Length
Sepal Width
Petal Length
Petal Width
This is a classic multi-class classification problem.
The Dataset
I chose the Iris dataset, which is one of the most famous datasets in the world of machine learning. It's perfect for beginners because:
It's small and easy to load.
It doesn't require complex cleaning or preprocessing.
It's built right into the scikit-learn library!
Workflow (The ML Pipeline)
My approach follows the standard machine learning pipeline:
Data Loading: The script begins by loading the Iris dataset directly from scikit-learn.
Data Splitting: I split the dataset into two parts:
An 80% training set to teach the model.
A 20% testing set to evaluate how well the model performs on new, unseen data.
Model Selection: I chose Logistic Regression as the model. It's a great baseline for classification tasks because it's efficient, effective, and easy to interpret.
Training: The model learns patterns and relationships from the training data using the .fit() method.
Evaluation: Finally, the trained model makes predictions on the test set. I calculated the accuracy to see what percentage of flowers it classified correctly.
Results
The model performs exceptionally well on this dataset!
Accuracy on the test set: 100.00%
This high accuracy is common for the Iris dataset with simple models, which confirms that our pipeline is working correctly. The script also prints a few examples of its predictions versus the actual labels.
How to Run This Project
You can get this running on your machine in just a few steps.
Clone the Repository
git clone [your-github-repository-url]
cd [repository-folder]
Install the Dependencies
Make sure you have Python installed. Then, run this command in your terminal to install the necessary libraries.
pip install -r requirements.txt
Run the Script!
Execute the Python script to see the magic happen.
python model.py
You'll see the output in your terminal, walking you through each step of the process and showing the final accuracy.
Thanks for checking out my project! 
