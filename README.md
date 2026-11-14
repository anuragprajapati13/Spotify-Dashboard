# 🎵 Spotify Top 50 Music Analytics Dashboard | Power BI

An interactive **Spotify Top 50 Music Analytics Dashboard** developed using Microsoft Power BI to explore music trends, artist performance, song popularity, album distribution, and other key insights from Spotify chart data.

This project transforms music data into meaningful visual insights through interactive dashboards, dynamic filtering, and DAX-powered KPIs.

## 📌 Project Overview

The Spotify Top 50 Music Analytics Dashboard provides an interactive platform for analyzing songs and artists using different performance metrics.

The dashboard is divided into three major analytical sections:

- **Overview:** Provides a high-level summary of music statistics and trends.
- **Artist Analysis:** Explores artist-wise performance, song counts, popularity, and chart achievements.
- **Song Analysis:** Examines individual song performance, popularity, and ranking-related metrics.

The goal is to understand music trends and identify patterns in song popularity and artist performance.

## 🎯 Project Objectives

- Analyze the overall Spotify song collection.
- Identify artists with the highest number of songs.
- Evaluate song popularity and artist performance.
- Analyze explicit and non-explicit song distribution.
- Compare album types, including singles and albums.
- Explore song performance across different years and months.
- Identify songs and artists achieving the No. 1 chart position.
- Build an interactive dashboard for music data exploration.

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development |
| Power Query | Data transformation |
| DAX | Measures and KPI calculations |
| Data Visualization | Interactive charts and reports |
| Power BI Custom Visuals | Enhanced dashboard interaction |

## 📊 Dashboard Pages & Features

### 1. Overview Dashboard

Provides a comprehensive summary of Spotify music data.

**Key Features:**
- Total Songs
- Distinct Songs
- Distinct Artists
- Average Popularity
- Average Song Duration
- Songs by Artist
- Monthly Popularity Trends
- Album Type Distribution
- Explicit vs. Non-Explicit Songs
- Year-Wise Song Distribution
- Popularity Analysis by Album Type

### 2. Artist Analysis Dashboard

Focuses on analyzing individual artist performance.

**Key Features:**
- Songs by Artist
- Popularity of Artists
- Total No. 1 Hits per Artist
- Artist-Wise Performance Comparison
- Artist-Specific Song Selection
- Song Popularity Analysis
- Detailed Artist and Song Information

### 3. Song Analysis Dashboard

Provides detailed insights into individual songs.

**Key Features:**
- Songs by Artist
- Songs by Popularity
- Hit Songs per Artist
- Song Popularity Comparison
- Song Selection with Album Artwork
- Song Details and Release Information
- Interactive Song-Level Analysis

## 📐 DAX Measures

This project uses DAX (Data Analysis Expressions) to calculate important analytical metrics.

Some of the implemented measures include:

| Measure | Description |
|---|---|
| Total Songs | Counts total song records |
| Distinct Songs | Counts unique song names |
| Distinct Artists | Counts unique artists |
| Avg Popularity | Calculates average song popularity |
| Max Popularity | Finds the highest popularity score |
| Avg Duration Minutes | Calculates average song duration |
| Explicit Songs | Counts explicit songs |
| Non-Explicit Songs | Counts non-explicit songs |
| Pct Explicit Songs | Calculates the percentage of explicit songs |
| Avg Position | Calculates average chart position |
| Position 1 Songs | Counts songs reaching position 1 |
| Position 1 Artists | Counts artists associated with position 1 |
| Avg Tracks per Album | Calculates average tracks per album |

Additional artist-specific and year-specific measures are also implemented.

## 📈 Visualization Techniques

The dashboard uses multiple visualization techniques to make music data easier to understand.

- Clustered Bar Charts
- Clustered Column Charts
- Area Charts
- Donut Charts
- 100% Stacked Bar Charts
- KPI Cards
- Interactive Slicers
- Data Tables
- Album Artwork and Image Visuals

## 🔍 Interactive Features

The dashboard provides interactive elements to explore music data dynamically.

- Artist selection
- Song selection
- Year-based analysis
- Album type filtering
- Dynamic visual interactions
- Cross-filtering between visualizations

Users can select different artists and songs to explore their corresponding performance metrics.

## 💡 Key Analytical Questions

This dashboard helps answer questions such as:

1. Which artists have the highest number of songs?
2. Which songs have the highest popularity?
3. Which artists have achieved the most No. 1 chart positions?
4. What is the distribution of explicit and non-explicit songs?
5. How are songs distributed across different album types?
6. How does average song popularity change over time?
7. What is the average duration of songs?
8. Which artists and songs perform better based on popularity?

## 📁 Project Structure

```text
Spotify-Music-Analytics/
│
├── README.md
│
├── SpotifyDashboard.pbix
│
└── screenshots/
    ├── overview.png
    ├── artist-analysis.png
    └── song-analysis.png
```

*Note: The screenshots folder is suggested. Add your dashboard screenshots to it.*

## ⚙️ How to Run the Project

Follow these steps to explore the dashboard:

**Step 1:** Clone the repository.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2:** Navigate to the project directory.

```bash
cd Spotify-Music-Analytics
```

**Step 3:** Download and install Microsoft Power BI Desktop.

**Step 4:** Open `SpotifyDashboard.pbix` in Power BI Desktop.

**Step 5:** Explore the Overview, Artist, and Songs pages.

**Step 6:** Use interactive slicers and visualizations to analyze the data.

## 🚀 Future Enhancements

- Add advanced year-over-year popularity comparisons.
- Implement additional artist ranking metrics.
- Include audio feature analysis such as danceability, energy, and tempo if available in the dataset.
- Add advanced music trend forecasting.
- Improve report navigation and drill-through functionality.
- Integrate updated Spotify datasets for more recent analysis.

## 🎓 Skills Demonstrated

- Data Analytics
- Business Intelligence
- Microsoft Power BI
- Data Cleaning and Transformation
- DAX Measures
- Data Visualization
- KPI Development
- Interactive Dashboard Design
- Analytical Thinking
- Data-Driven Decision Making

## 👨‍💻 Author

**Anurag Prajapati**

B.Tech Computer Science & Engineering | Data Science

**Areas of Interest:** Data Analytics | Data Visualization


---

⭐ If you find this project interesting, don't forget to star the repository!

**Thanks for visiting!**
