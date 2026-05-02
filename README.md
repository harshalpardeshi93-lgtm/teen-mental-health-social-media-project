# teen-mental-health-social-media-project
# Social Media Impact on Teen Mental Health

This project analyzes how teenagers' social media habits, sleep patterns and lifestyle factors relate to
their mental health and academic performance.

## Problem

Given a group of teenagers with different social media usage, sleep duration and lifestyle habits,
which profiles appear most at risk for mental-health issues (stress, anxiety, addiction, depression),
and how do these patterns impact academic performance?

## Data

- Teen mental-health survey with:
  - Age, gender
  - Daily social media hours and platform (Instagram / TikTok / Both)
  - Sleep hours and screen time before sleep
  - Physical activity and social interaction level
  - Stress, anxiety, addiction scores and depression label

Clean and feature-engineered data is stored in `data/Teen_Mental_Health_Project_Data.xlsx`.

## What I built

- **Teen Risk Index (0–100)** combining social media hours, sleep deficit, stress, anxiety and addiction.
- **Usage bands** (0–2h, 2–4h, 4–6h, 6–8h, 8h+) vs stress, anxiety, sleep and grades.
- **Sleep pathway view**: High/Low use × Short/Adequate sleep.
- **Personas**: "Always‑online night owl", "Balanced user", "Low‑use high‑support".
- **What-if insight**: compares high‑use + short sleep vs low‑use + adequate sleep groups.

The main dashboard is `web/teen-mental-health-advanced-dashboard-animated-mind.html`.
The full write‑up is in `report/Teen_Mental_Health_Project_Report.docx`.
