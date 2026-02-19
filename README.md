YouTube Channel Performance Analyzer

Objective:
Analyze YouTube channels using real-time data from the YouTube Data API
and rank them based on engagement rate.

Data Source:
Official YouTube Data API v3

Metrics Used:
- Subscribers
- Total Views
- Average Likes (last 10 videos)
- Average Comments (last 10 videos)
- Engagement Rate
- Video Titles (recent videos)
- Upload Frequency (videos per week)

Engagement Formula:
(Average Likes + Average Comments) / Subscribers * 100

Output:
Results are sorted by engagement rate (highest first).
The output includes video titles from recent videos and upload frequency 
(videos per week) calculated from the publish dates of recent videos.

Notes:
Only public data is used. API-based approach ensures accuracy
and compliance with platform policies.

Setup:
- Create a `.env` file (copy `.env.example`) and set `YOUTUBE_API_KEY`.
