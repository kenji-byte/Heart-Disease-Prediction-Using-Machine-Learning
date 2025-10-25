# Heart-Disease-Prediction-Using-Machine-Learning
A machine learning project using the UCI Heart Disease Dataset to predict the presence of heart disease based on patient health attributes. The main goal of the project was to build a predictive model that can assist in early diagnosis, helping healthcare professionals take timely preventive measures.


🚀 Model & Evaluation

The core of this project is a Gaussian Naive Bayes classifier. The model's performance was evaluated on the dataset, achieving the following result:

Accuracy: 85.33%

Further evaluation metrics, including a detailed Confusion Matrix and Classification Report, are available within the project's analysis notebook.

📊 Key Features & Visualizations

This repository includes a complete data analysis workflow:

Data Preprocessing: Cleaning and preparing the UCI dataset for modeling.

Correlation Heatmap: A visualization to understand the relationships between different medical attributes.

Model Training: Implementation of the Gaussian Naive Bayes algorithm.

ROC Curve: A graphical plot illustrating the diagnostic ability of the classifier.

🔧 Technologies Used

The project is built using the standard Python data science and machine learning stack:

Python

Pandas (for data manipulation and analysis)

NumPy (for numerical operations)

Scikit-learn (sklearn) (for machine learning modeling and evaluation)

Matplotlib / Seaborn (for data visualization)

💡 Future Scope

This project serves as a strong baseline. Future development could include:

Model Comparison: Implementing and evaluating other classifiers (e.g., Logistic Regression, SVM, Random Forest) to compare performance.

Hyperparameter Tuning: Optimizing model parameters using techniques like GridSearch CV to potentially improve accuracy.

Web Application: Deploying the trained model as a simple web application (using Streamlit or Flask) for interactive predictions.

📂 How to Use

To run this project locally, clone the repository and install the required dependencies:

# Clone the repository
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name

# Install dependencies (assuming you have a requirements.txt)
pip install -r requirements.txt

# Or manually install
pip install pandas numpy scikit-learn matplotlib seaborn

# Run the notebook or script
python <main.py>

