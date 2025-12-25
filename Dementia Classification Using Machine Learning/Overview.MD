Overview
This project explores the application of machine learning techniques for classifying dementia status using clinical and MRI related data. Dementia is a progressive neurological condition, and early identification plays an important role in supporting timely clinical decisions. The objective of this project is to analyze patient level data and develop predictive models that can distinguish between demented and non demented individuals.

Dataset
The dataset used in this project is obtained from the Open Access Series of Imaging Studies OASIS 2. It contains longitudinal MRI data from 150 subjects with multiple scanning sessions. The dataset includes demographic information, cognitive assessment scores, and imaging related features commonly used in dementia research.

Methodology
The project follows a structured machine learning workflow starting with exploratory data analysis to understand data distributions, correlations, and class balance. Irrelevant and identifier columns such as subject ID, MRI ID, hand, visit, and MR delay are removed to prevent data leakage.

Data preprocessing steps include handling missing values, encoding categorical variables, and applying feature scaling where required. Multiple supervised learning models are trained and evaluated, including a Support Vector Machine as a baseline model and a Gradient Boosting model to capture more complex patterns in the data.

Results and Evaluation
Model performance is evaluated using standard classification metrics. The Gradient Boosting model outperforms the baseline Support Vector Machine, demonstrating stronger predictive capability and better handling of non linear relationships among features. These results highlight the effectiveness of ensemble learning methods for dementia classification tasks.

Conclusion
This project demonstrates how machine learning can be applied to medical and clinical datasets to support dementia classification. The findings suggest that advanced ensemble models can provide meaningful improvements over traditional baseline approaches, reinforcing the potential of data driven methods in healthcare related decision support.

Tools and Techniques
Python
pandas, numpy, scikit learn, matplotlib, seaborn
Exploratory data analysis, data preprocessing, supervised learning, model evaluation

