# 🌾 Predicting Droughts in the US with Machine Learning
This project was one of my favorite collaborations during my Master’s program at San Jose State University, where we tackled a real-world challenge: Can we predict drought severity using just meteorological data?
With climate change making droughts more frequent and severe, I wanted to explore how machine learning could empower early warnings and proactive measures—whether for farmers, policymakers, or environmental agencies.

🛠️ What I Did:
✅ Worked with 2.7 million+ records from the US Drought Monitor, covering 18 key weather indicators like temperature, wind speed, humidity, and precipitation.
✅ Cleaned and prepared the data by filtering out incomplete records, detecting and removing outliers, and normalizing features.
✅ Balanced the dataset (because 80% of records belonged to a single drought category!) using both SMOTE upsampling and NearMiss downsampling—a tricky but rewarding part of the process.
✅ Explored the data visually using histograms, scatterplots, correlation heatmaps, and boxplots to really understand how variables interacted
✅ Selected the best features using Recursive Feature Elimination (RFE) with Random Forest—which helped narrow down from 23 to 15 key predictors.
✅ Reduced dimensionality with PCA to simplify the model without losing valuable insights.

🤖 Built and compared four machine learning models:
  Decision Tree
  K-Nearest Neighbors (KNN)
  Naïve Bayes
  Random Forest

I didn’t just want to see which performed best by accuracy—I wanted to evaluate them from multiple angles, so I measured:

Precision
Recall
F1 Score
Cohen’s Kappa
Class-wise ROC curves

(And yes… I spent hours tuning hyperparameters and optimizing settings! 😄)

💡 What made this project unique:
✨ I combined upsampling and downsampling techniques together to tackle class imbalance from both ends—a challenge that many studies skip.

✨ I took a multi-step approach to feature selection: starting with correlation analysis, then using Random Forest-based RFE, and finally PCA to streamline dimensionality.

✨ I managed the project using agile methodology, including daily standups, sprints on Trello, and pair programming over GitHub and Google Docs—this really sharpened my collaborative and project management skills.

✨ We even saved our trained models using Pickle for reuse and demo purposes.

📈 Key results I’m proud of:
✅ Random Forest turned out to be the star, achieving:

80.89% accuracy

Strong precision, recall, and F1 score across all classes

Best Cohen’s Kappa for agreement

✅ KNN followed closely with 79.87% accuracy, proving that simpler models still have power when tuned right.

✅ Decision Tree performed decently (76.33%) after hyperparameter tuning, but Naïve Bayes lagged behind at 58%—highlighting how critical model choice is for nonlinear, imbalanced data.

🌍 Why this project matters to me:
This wasn’t just a coding exercise—it made me realize how data-driven insights can inform climate resilience strategies. I was fascinated by how much predictive power lies in seemingly simple weather indicators. And I learned firsthand how important it is to balance accuracy with interpretability, fairness, and computational efficiency.
