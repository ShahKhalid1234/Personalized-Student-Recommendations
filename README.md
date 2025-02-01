 Student Performance Analysis and Recommendations

Project Overview
This project analyzes student performance data from quizzes and provides actionable insights to help improve learning outcomes. The system processes data from three main sources: quiz endpoints, quiz submissions, and API endpoints. It generates insights such as performance by topic, identifies weak areas, suggests improvement trends, and provides personalized recommendations to enhance future performance.

 Data Sources
- Quiz Endpoint Data: Provides information about various quizzes, including topics, time, and questions.
- Quiz Submission Data: Contains the results of student quiz attempts, including scores, accuracy, and other performance metrics.
- API Endpoint Data: Includes detailed submission records and performance details such as accuracy, speed, and overall score.

Data provided by **Testline**.

## Installation Instructions
1. Clone the repository:
   
git clone https://github.com/shahkhalid1234/Personalized-Student-Recommendations.git

2. Install required Python libraries:
   
   pip install -r requirements.txt
   

4. Upload your JSON files to Colab or your local environment to test the script.

## Approach and Logic
1. **Data Preprocessing**: Clean and format the quiz, submission, and API endpoint data. This includes handling missing values and converting data types where necessary.
2. **Exploratory Data Analysis (EDA)**: Visualize performance by topic, difficulty, accuracy, and other metrics. Identify trends and patterns.
3. **Performance Insights**: Calculate average scores and accuracy for each topic, highlight weak areas, and track improvement trends.
4. **Recommendations**: Based on the performance, suggest topics, question types, and difficulty levels that the student should focus on to improve.

## Key Features
- **Topic Performance Analysis**: Identifies top-performing and underperforming topics.
- **Improvement Trends**: Tracks changes in a student's performance over time.
- **Weak Area Identification**: Flags topics that need additional focus.
- **Actionable Recommendations**: Provides personalized suggestions based on individual quiz results.


