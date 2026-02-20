# Tweet-Interactions-by-Category-3-5PM-IST-

📊 Tweet Interactions Dashboard (3–5 PM IST)
📌 Project Overview

This project is a Power BI Dashboard that analyzes tweet engagement metrics during a specific time window (3:00 PM – 5:00 PM IST).

The dashboard provides insights into user interactions such as likes, URL clicks, profile visits, and hashtag clicks. It also includes a dynamic DAX measure that controls visual visibility based on the current time.

🎯 Objective

Analyze tweet engagement performance.

Monitor interaction metrics within a specific time window.

Implement time-based logic using DAX.

Create an interactive and dynamic reporting experience.

📊 Key Performance Indicators (KPIs)

Count of Tweets (ID): 1.17K

Total Likes: 8K

Total URL Clicks: 3K

Total User Profile Clicks: 3K

Total Hashtag Clicks: 303

These KPIs provide a quick overview of tweet engagement performance.

📈 Dashboard Visuals

Hashtag Click Distribution

Shows how hashtags perform across tweets.

Helps identify high-performing hashtags.

URL Click Analysis

Displays traffic generated through tweet links.

Identifies strong call-to-action content.

Profile Click Analysis

Measures user interest in the profile.

Indicates potential brand growth opportunities.

🧠 DAX Logic Used

ShowVisual = 
VAR CurrentTime = NOW()
RETURN
IF(
    HOUR(CurrentTime) >= 15 &&
    HOUR(CurrentTime) < 17,
    1,
    0
)

🔎 Explanation

NOW() returns the current date and time.

HOUR() extracts the hour.

The condition checks if time is between 3 PM (15) and 5 PM (17).

Returns 1 → Show visuals.

Returns 0 → Hide visuals.

This makes the dashboard time-controlled and dynamic.

⚙️ Tools & Technologies

Power BI

DAX (Data Analysis Expressions)

Data Visualization Techniques

🚀 Features

Interactive KPI Cards

Dynamic Chart Visibility

Time-Based Filtering

Clean and Dark Themed Dashboard

📷 Dashboard Preview

(Add screenshots here)

📚 Learning Outcome

Improved understanding of DAX time functions.

Learned how to control visual visibility dynamically.

Enhanced dashboard design and storytelling skills.

👤 Author

Mandar Kolhe
