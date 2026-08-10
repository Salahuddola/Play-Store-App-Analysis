# Play-Store-App-Analysis
Play Store App Data Analysis (AlmaBetter Module 2 Capstone Project)
An end-to-end Exploratory Data Analysis (EDA) project on the Google Play Store dataset to analyze app metrics, user ratings, installations, pricing strategies, and sentiment dynamics from customer reviews.

📌 Project Overview
The primary objective of this project is to perform comprehensive data cleaning, feature engineering, exploratory data analysis, and sentiment analysis on two main datasets:

Play Store Apps Data: Contains details such as App Category, Rating, Reviews, Size, Installs, Type (Free/Paid), Price, Content Rating, and Genres.

User Reviews Data: Contains customer reviews along with pre-calculated sentiment scores (Translated_Review, Sentiment, Sentiment_Polarity, Sentiment_Subjectivity).

By analyzing these datasets, we uncover actionable insights for app developers, marketers, and product managers to improve app performance, visibility, and user retention.

🛠️ Tech Stack & Libraries
Language: Python

Data Manipulation: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Development Environment: Google Colab / Jupyter Notebook

Version Control: Git, GitHub

🧹 Data Cleaning & Preprocessing
Handling Missing Values: Imputed null values in Rating using median strategy and filled missing categorical variables like Type and Content Rating.

Data Type Conversion:

Converted Installs from string with symbols (e.g., 10,000+) to clean integer format.

Processed Size into a uniform numeric scale (MBs), converting k to bytes/MB equivalent and handling 'Varies with device'.

Converted Price into numeric float values after removing the $ currency sign.

Cast Reviews column into integer format.

Outlier Treatment & Duplicate Removal: Identified and removed duplicate app records to avoid skewed statistical metrics.

📊 Key Insights & Exploratory Analysis
Category Dominance:

Categories like Family, Game, and Tools account for the largest volume of apps on the Play Store.

Game and Communication categories lead in terms of total user downloads/installs.

Free vs. Paid Apps Strategy:

Over 92% of the apps on the Play Store are Free, proving that freemium or in-app ad models are the dominant monetization strategies.

Paid apps generally maintain higher average user ratings, though their overall download volumes are significantly lower.

Ratings Distribution:

User ratings are heavily skewed toward the higher end (between 4.0 and 4.7), indicating strong overall satisfaction or selective reporting bias.

Size vs. Installs:

Apps within moderate size ranges (10MB - 50MB) enjoy broader adoption, while excessively large file sizes can act as a barrier to initial installs on lower-end devices.

User Sentiment Dynamics:

Sentiment Analysis on user reviews reveals a strong positive sentiment bias across top-rated apps, while negative reviews heavily correlate with issues around app crashes, frequent ads, and performance bugs.

📂 Repository Structure
Plaintext
├── playstore_reviews.ipynb    # Main Colab Jupyter Notebook containing code & visual plots
├── README.md                  # Project overview and key takeaways
🚀 How to Run
Clone the repository:

Bash
git clone https://github.com/Salahuddola/Play-Store-App-Analysis.git
Open playstore_reviews.ipynb in Google Colab or your local Jupyter Notebook setup.

Install the required dependencies:

Bash
pip install pandas numpy matplotlib seaborn
Run all cells sequentially to view data cleaning steps and generated interactive visual plots.

👤 Author
Sultan Salahuddola

GitHub Profile
