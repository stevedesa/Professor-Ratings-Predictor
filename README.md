# Professor Ratings Predictor 📊🎓

This project is a natural language processing (NLP) application that predicts professor ratings (1 to 5 stars) based on student-written reviews. Developed for the final project in CSC 448 - Natural Language Processing, the model was built entirely from scratch using only core Python libraries (`NumPy`, `Pandas`, `Matplotlib`), without any high-level ML frameworks like scikit-learn or TensorFlow.

## 🔍 Project Description

The core task is to classify text reviews into discrete rating classes (1 to 5) using a logistic regression model. The pipeline includes:

- **Data Exploration**: Visualizing rating distribution and key word frequencies.
- **Preprocessing**: Cleaning and tokenizing review text.
- **Feature Engineering**: Building a custom TF-IDF vectorizer.
- **Model Development**: Implementing multi-class logistic regression from scratch.
- **Evaluation**: Performing 5-fold cross-validation to assess generalization.

## 📈 Results

The final model was evaluated using cross-validation and achieved a balanced performance across all five classes. Graphs and accuracy scores are presented in the notebook.

## 🤖 Model Highlights

- Custom gradient descent implementation
- In-house TF-IDF vectorizer
- Strong interpretability of weights

## 🧠 Skills Applied

- Text preprocessing & feature extraction
- Multi-class classification
- Model evaluation & error analysis
- Data visualization

## 📸 Visuals

Plots showing class distribution, TF-IDF weights, and learning curves can be found in the `Images/` folder and are embedded within the notebook.
