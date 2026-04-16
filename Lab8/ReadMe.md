KNN Assignment

Project Description

This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm using the scikit-learn library.

The workflow includes:
	•	Data exploration (EDA)
	•	Feature scaling
	•	Model training
	•	Model evaluation
	•	Choosing the optimal value of K

⸻

Project Files
	•	KNN_Assignment_Solution.ipynb → Main notebook containing the full solution
	•	KNN_Project_Data → Dataset file

⸻

Requirements

Make sure you have the following libraries installed:

pip install pandas numpy matplotlib seaborn scikit-learn

⸻

How to Run
	1.	Open Jupyter Notebook or VS Code
	2.	Ensure the dataset file is in the same directory
	3.	Open the notebook:
KNN_Assignment_Solution.ipynb
	4.	Run all cells step by step

⸻

Methodology
	•	Load and inspect the dataset
	•	Explore relationships between variables using visualizations
	•	Scale the data using StandardScaler
	•	Split the data into training and testing sets
	•	Train a KNN classification model
	•	Make predictions
	•	Evaluate model performance using classification metrics
	•	Analyze error rate to select the best value of K

⸻

Key Observations
	•	Feature scaling is essential for KNN since it depends on distance calculations
	•	The choice of K has a strong impact on model performance
	•	Smaller K values can lead to overfitting
	•	Larger K values may reduce model accuracy
	•	The model improves after selecting the optimal K value

⸻

Conclusion

This assignment provided a clear understanding of how KNN works and how model performance can be improved through proper preprocessing and parameter tuning.
