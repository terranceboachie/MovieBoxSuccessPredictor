# MovieBoxSuccessPredictor
What makes a blockbuster? This project uses machine learning to predict box office success and reveal the hidden factors that turn movies into hits.

📌 Project Overview

Why do some movies become blockbusters while others flop?
This project explores that question using machine learning. I built a predictive model to determine whether a movie will be a box office success before release, based on factors like budget, popularity, runtime, audience ratings, and vote counts.

The project demonstrates end-to-end data science skills — from data collection and cleaning to model building, evaluation, and business insights.

🚀 Key Features

Data Collection & Cleaning: Processed a large movie dataset from TMDB (The Movie Database).

Exploratory Data Analysis (EDA): Identified patterns and correlations between features (e.g., popularity vs budget).

Model Development: Trained multiple ML models (Logistic Regression, Random Forest, Gradient Boosting).

Performance Evaluation: Achieved ~80% accuracy with confusion matrix results.

Feature Importance: Determined that vote count, popularity, and budget are the strongest predictors of box office success.

📊 Results
Confusion Matrix

True Negatives (414) and True Positives (345) → Model performs well on both hits and flops.

Misclassifications (99 + 103) highlight where more nuanced features could improve predictions.

Feature Importance (Top Predictors)

Vote Count → Audience engagement is the strongest driver.

Popularity → Buzz matters more than runtime.

Budget → Investment helps, but isn’t enough on its own.

💡 Business Insights

Movies with high audience engagement and buzz are more likely to succeed — regardless of runtime or critic ratings.

Studios can use this type of model to assess risk before green-lighting projects.

Marketing teams can identify where boosting engagement may shift a potential flop into a success.

⚙️ Tech Stack & Tools

Programming: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Platform: Google Colab, Google Drive for dataset management

Techniques: Data Cleaning, EDA, Feature Engineering, Machine Learning, Model Evaluation

📂 Project Structure
├── data/                # Raw and cleaned datasets  
├── notebooks/           # Jupyter/Colab notebooks  
├── visuals/             # Confusion matrix & feature importance plots  
├── README.md            # Project documentation  

🔮 Next Steps

Incorporate textual/movie script data for sentiment analysis.

Add genre and cast influence to improve predictive power.

Deploy as a web app (e.g., Streamlit) to allow users to input movie details and get predictions.

✨ Author

👤 Terrance Boachie 

💼 LinkedIn: linkedin.com/in/terrance-boachie

📧 Contact: terrencenanab@gmail.com
