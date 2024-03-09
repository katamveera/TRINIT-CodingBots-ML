# TRINIT-CodingBots-ML
Explainable Sexual Harassment Categorization System
# **Overview:**
The Explainable Sexual Harassment Categorization aims to classify instances of sexual harassment in text data while providing transparent explanations for the categorization decisions. This is essential for understanding the factors influencing the model's predictions and ensuring accountability and fairness in addressing sexual harassment.

# **Challenges in Explainable Sexual Harassment Categorization:**
1. **Data Quality:** Obtaining high-quality labeled datasets containing diverse examples of sexual harassment incidents.
2. **Interpretability:** Ensuring that the model's decision-making process is transparent and understandable, especially in sensitive domains like sexual harassment.
3. **Subjectivity:** Handling the subjective nature of sexual harassment perceptions and interpretations.
4. **Bias Mitigation:** Addressing biases present in the data and model predictions to ensure fairness and inclusivity.

# **Approach:**
1. **Data Collection:** Gather labeled datasets containing narratives or descriptions of sexual harassment incidents.
2. **Preprocessing:** Clean and preprocess the text data, including removing noise, standardizing formatting, and tokenization.
3. **Model Selection:** Choose appropriate machine learning or deep learning models for text classification, considering both accuracy and explainability.
4. **Training:** Train the selected models on the labeled dataset, optimizing for accuracy and interpretability.
5. **Explanation Techniques:** Apply explainable AI techniques such as SHAP or LIME to provide insights into the model's decision-making process.
6. **Evaluation:** Evaluate the model's performance using metrics like accuracy, precision, recall, and F1 score.
7. **Iterative Improvement:** Continuously refine and improve the model based on feedback and validation against real-world cases.

# **Dataset:**
The dataset consists of labeled examples of sexual harassment incidents, including text descriptions or narratives of the incidents and their corresponding categories.

# **Code Description:**
The Python code implements a basic rule-based approach to categorize text for potential sexual harassment using regular expressions. It categorizes text as "Potential Sexual Harassment" if specific keywords associated with harassment or assault are found, otherwise, it's categorized as "Not Classified." An explanation function provides context for the categorization decision.

# **Conclusion:**
The Explainable Sexual Harassment Categorization is crucial for addressing sexual harassment effectively, providing transparency, and accountability in decision-making processes. While the provided code offers a basic rule-based approach, more sophisticated machine learning models combined with explainable AI techniques can further enhance the accuracy and interpretability of sexual harassment categorization systems.
