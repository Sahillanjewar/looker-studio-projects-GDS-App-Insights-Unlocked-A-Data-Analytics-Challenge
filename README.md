# looker-studio-projects-GDS-App-Insights-Unlocked-A-Data-Analytics-Challenge
This project analyzes Google Play Store app data to uncover patterns and trends that influence app success. The objective is to identify factors contributing to high ratings, installs, and user engagement.
Dataset Source:
Kaggle – Google Play Store Apps Dataset
🎯 Problem Objectives

Identify key factors that contribute to app success
This involves analyzing ratings, installs, reviews, pricing, and updates to determine what makes an app perform well on the Play Store.

Understand what drives high ratings and installs
The goal is to discover patterns that influence user satisfaction and download behavior.

Discover the most popular and high-performing categories
This helps in identifying which app categories attract the highest engagement and installs.

Analyze the impact of app size and pricing on user behavior
This examines whether smaller apps or free apps perform better in terms of downloads and ratings.

Generate insights for data-driven decisions
The analysis supports strategic planning in development, marketing, and monetization.

👥 Stakeholders
Internal Stakeholders

App Developers
Developers can use insights to improve app quality, features, and update frequency.

Product Managers
Product managers can prioritize features and categories based on performance trends.

Marketing Team
Marketing teams can design targeted campaigns based on user behavior insights.

Senior Management
Leadership can use findings for strategic investments and business expansion decisions.

External Stakeholders

App Users
Users benefit from improved app quality and better user experience.

Advertisers
Advertisers can target high-performing categories for better ROI.

Business/Tech Partners
Partners can align collaborations with trending and high-demand app categories.

🧹 Data Cleaning & Preprocessing

Handled missing values
Missing ratings and inconsistent entries were cleaned to ensure accurate analysis.

Converted Installs and Price into numeric format
Text-based values like “1,000+” were converted into numerical form for proper calculations.

Standardized app size into MB
Different size formats were unified into MB for consistency in analysis.

Removed duplicate records
Duplicate apps were eliminated to avoid misleading insights.

Standardized Category and Genre text fields
Inconsistent naming formats were corrected to maintain uniformity.

Converted Last Updated into datetime format
Date values were formatted properly to analyze update trends over time.

📊 Metrics Developed

Average Rating
Measures overall user satisfaction across apps.

Total Installs
Indicates overall popularity and demand for apps.

Total Reviews
Reflects user engagement and feedback levels.

Revenue Potential (Paid Apps × Installs)
Estimates possible revenue generation from paid apps.

Category-wise Performance
Compares how different categories perform based on installs and ratings.

🔎 Basic Analysis

Average app rating
Helps understand the general satisfaction level of apps on the platform.

Free vs Paid distribution
Shows the market split between monetization models.

Most common content rating
Identifies the primary target audience age group.

Top installed apps
Highlights the most successful apps in terms of downloads.

Category distribution
Shows how apps are spread across different categories.

🔎 Intermediate Analysis

Correlation between installs and ratings
Examines whether more popular apps also have higher ratings.

Category-wise average rating
Identifies which categories deliver better user satisfaction.

Price vs rating relationship
Analyzes whether paid apps receive better ratings than free apps.

App size vs installs
Determines if smaller apps attract more downloads.

Update frequency patterns
Studies how regular updates influence app ratings and installs.

🔎 Advanced Analysis

Binned install vs rating analysis
Groups apps by install ranges to observe rating trends across popularity levels.

Genre-based performance trends
Identifies which genres consistently perform well in terms of ratings and installs.

Update trend over time
Analyzes how frequently apps are updated across different years.

High-rated apps benchmarking
Studies top-rated apps to understand best practices.

User engagement insights
Evaluates review patterns to understand user behavior.

🛠 Tools & Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)
Used for data cleaning, analysis, and visualization.

SQL
Used for structured querying and data manipulation.

Looker Studio
Used to create interactive dashboards for business insights.

Jupyter Notebook
Used to document and execute the analysis step-by-step.

GitHub
Used for version control and project documentation.

🎓 Learning Outcome

Data Cleaning Skills
Improved ability to handle raw and inconsistent datasets.

Analytical Thinking
Developed the skill to connect data patterns with business impact.

Visualization Expertise
Learned how to present insights clearly through dashboards.

Strategic Recommendation Building
Gained experience in converting analysis into actionable business decisions
