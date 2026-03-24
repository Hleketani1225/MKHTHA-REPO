# Analyzing Amazon Consumer Behaviour Dataset

### Executive Summary:

Machine learning models were used to analyze Amazon customer purchasing behavior using a Kaggle dataset. Random Forest delivered the highest accuracy (76%), while hyperparameter tuning notably improved k-Nearest Neighbors. The study highlights the importance of model selection and tuning and shows that e-commerce purchasing decisions are influenced by multiple demographic, behavioral, and product-related factors.

Dataset:

Amazon Consumer Behaviour Dataset (Kaggle)

https://www.kaggle.com/datasets/swathiunnikrishnan/amazon-consumer-behaviour-dataset


### Business Problem:

Amazon’s rapid e-commerce growth produces extensive and complex customer datasets, making it challenging to predict purchasing behavior. This project evaluated multiple machine learning models to uncover the most effective methods for forecasting customer decisions.
####

### Methodology:

* Data Preparation (Python): Imported the Amazon Consumer Behaviour dataset from Kaggle (CSV format) and performed data cleaning, preprocessing, and transformation using Python libraries such as Pandas, Matplotlib, and NumPy.
* Business Intelligence Dashboard (Tableau): Built an interactive Tableau dashboard to track order status trends, visualize key metrics, and deliver actionable insights to support business decisions.

### Results & Discussion:

The models were evaluated on a dataset of 602 entries with 23 features using an 80/20 train-test split. Random Forest performed best, achieving 76% accuracy with strong precision and F1-score. After hyperparameter tuning, k-Nearest Neighbors (k-NN) improved from 65% to 73%, Random Forest and XGBoost showed slight declines, and Gaussian Naive Bayes remained unchanged.

These results highlight the importance of algorithm selection and tuning for predictive accuracy. Analysis also showed that customer purchasing behaviour is shaped by multiple factors, including age, gender, price sensitivity, convenience, satisfaction, purchase frequency, product type, and product quality.

### Conclusion

Random Forest outperformed Gaussian Naive Bayes, k-NN, and XGBoost in analysing Amazon customer purchasing behaviour, maintaining strong accuracy even after tuning. k-NN improved notably with parameter optimization, showing the value of fine-tuning simpler models. The study also found that purchasing behaviour is influenced by demographic, behavioural, and contextual factors that is, age, gender, price sensitivity, convenience, satisfaction, purchase frequency, product type, and product quality. Overall, ensemble models like Random Forest are effective for uncovering complex consumer patterns, offering insights for recommendation systems and targeted marketing
