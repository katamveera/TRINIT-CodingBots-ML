# TRINIT-CodingBots-ML
Explainable Sexual Harassment Categorization System
# **Overview:**
The Explainable Sexual Harassment Categorization aims to classify instances of sexual harassment in text data while providing transparent explanations for the categorization decisions. This is essential for understanding the factors influencing the model's predictions and ensuring accountability and fairness in addressing sexual harassment.

# **Challenges in Explainable Sexual Harassment Categorization:**
Understanding the factors/features that contribute to sexual harassment incidents.
Explaining the decision-making process of machine learning models in identifying sexual harassment incidents.
Ensuring transparency and interpretability in the classification process.

# **Approach:**
Tokenization, stop-word removal, and vectorization of textual descriptions using TF-IDF (Term Frequency-Inverse Document Frequency).
Training an SVM classifier with a linear kernel on the vectorized textual data.
Using SHAP (Kernel Explainer) to compute the SHAP values, which represent the impact of each feature on the model's output.
Evaluating the model's performance using the Hamming Score for multi-classification.

# **Dataset:**
The dataset contains textual descriptions of sexual harassment incidents.
It includes features such as the description of the incident and the corresponding label indicating the type of harassment.

# **Code Description:**
The code loads the dataset and performs data preprocessing steps such as vectorization and splitting into training and testing sets.
It trains an SVM classifier on the training data and computes SHAP values using a Kernel SHAP explainer.
The SHAP values are visualized using a summary plot.
Evaluation metrics such as the Hamming Score, identity accuracy, separability score, similarity score, and stability score are computed.
These metrics provide insights into the model's performance, interpretability, and robustness.

# **Conclusion:**
The code demonstrates an approach to classify sexual harassment incidents using machine learning techniques while providing explanations for the model's decisions.
It highlights the importance of explainability in sensitive domains such as sexual harassment categorization.
The evaluation metrics help assess the model's performance and interpretability, contributing to transparency and accountability in the classification process.
