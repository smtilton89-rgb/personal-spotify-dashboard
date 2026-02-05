# personal-spotify-dashboard
Personal Spotify Listening Dashboard (Power BI)

## Project Overview
This project analyzes my personal Spotify streaming history to explore listening habits, time-based patterns, and artist preferences. The goal was to practice Power BI data modeling, Power Query transformations, and dashboard storytelling using real-world, imperfect data.

## Data Source
Data was sourced from Spotify’s Personal Data Export, provided as JSON files.  
The dataset includes track-level listening history with timestamps and play duration.

To protect privacy, raw data files are not included in this repository.

## Tools & Technologies
- Power BI Desktop  
- Power Query  
- DAX  
- Spotify  

## Data Preparation
Data preparation included:
- Parsing and expanding nested JSON records
- Converting timestamps and data types
- Creating derived time fields (date, hour, weekday)
- Converting milliseconds played into minutes
- Filtering out accidental plays under 30 seconds

## Key Metrics & Visuals
- Total minutes played
- Total streams
- Unique artists
- Listening by hour of day
- Listening by weekday
- Top tracks and artists by total listening time
- Monthly listening trends

## Insights
- Listening peaks in the late afternoon and early evening
- Early weekdays show higher listening volume than weekends
- A small number of artists account for a large share of listening time
- Listening volume declines during summer months and increases toward the end of the year

## Notes
This project was created for learning and portfolio purposes using personal data.
