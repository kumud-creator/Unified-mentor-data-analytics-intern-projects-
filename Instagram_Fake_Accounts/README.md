Objective
To detect and classify fake, spam, and genuine Instagram accounts using machine learning models based on user behavior, engagement metrics, and profile features.

## Tools & Technologies
- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Machine Learning:** Random Forest Classifier
- **Evaluation Metrics:** Accuracy, Precision, Recall, Confusion Matrix
- **Visualization:** Tableau, Seaborn

## Process Overview
1. Processed and labeled dataset with 576 Instagram accounts.
2. Cleaned and standardized features like follower count, post count, bio length, and profile pic status.
3. Split data into training and testing sets.
4. Built classification model to detect fake accounts.
5. Evaluated performance using confusion matrix and accuracy metrics.

## Challenges Faced
- Managing imbalanced data distribution between fake and genuine accounts.
- Converting behavioral metrics into numerical form.
- Avoiding model overfitting and maintaining interpretability.

## Results & Insights
- Model achieved **~90% accuracy** using Random Forest Classifier.
- Key predictive features: **profile picture**, **post count**, and **follower–following ratio**.
- Visualization revealed strong behavioral differences between fake and genuine profiles.

## Key Learnings
- Feature selection and importance ranking.
- Binary classification and model validation techniques.
- Application of ML to social media security analytics.
