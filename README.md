# FUTURE_DS_03
“Conducted NLP-based student feedback analysis for Task 3 of the Future Interns Internship using VADER and TextBlob to perform sentiment analysis, word cloud generation, and gap analysis.”

📌 Project Overview :

The objective of this project was to analyze student feedback data to understand the "voice of the student". By applying Natural Language Processing (NLP) techniques, I identified key satisfaction drivers and pinpointed specific areas (like Wifi and Campus facilities) that require administrative attention.

🛠️ Technical Workflow :

Data Cleaning: Used Regex to strip special characters and normalized text for processing.

Sentiment Scoring: Implemented both TextBlob and NLTK VADER to categorize feedback into Positive, Neutral, and Negative sentiments.

Trend Analysis: Resampled data by month to track how student satisfaction evolved over the academic year.

Gap Analysis: Calculated the "performance gap" between individual facilities and the university-wide average score.

Key Features (Technical Highlights):

Multi-Engine Sentiment Analysis: Implemented both TextBlob for polarity and NLTK VADER for compound sentiment scoring to ensure high accuracy.

Text Preprocessing: Built custom cleaning pipelines using Regex to normalize text by removing special characters and noise.

Time-Series Tracking: Developed a monthly satisfaction trend analysis to monitor how student sentiment fluctuates throughout the academic year.

Advanced Visualizations: Created Word Clouds to identify recurring issues in negative feedback and Correlation Heatmaps to see how specific facility ratings (like Wifi) impact the overall score.

Performance Gap Analysis: Automated a comparison between individual facility performance and the university-wide average to highlight areas of underperformance.

🗝️ Actionable Insights :

Pain Point Discovery: The analysis revealed that students in the 'Negative' category frequently mention "Wifi" and "Slow" connections as primary frustrations.

Correlation: A heatmap confirmed a strong correlation between Campus ratings and the Overall Satisfaction score, suggesting campus environment is a top priority for students.

Executive Summary: The average satisfaction stands at 4.43 / 5.0 , with CAMPUS being the highest-rated area.

🚀 How to Run the Analysis:

Ensure you have the reviews.csv file in the root directory.

Install dependencies: pip install pandas seaborn matplotlib textblob nltk wordcloud (everything available within Google colab)

Run the script: python students_response_feedback_study.py.
