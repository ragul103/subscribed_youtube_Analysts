# 📈 YouTube Analysts – Most Subscribed Channels Insights

## 🔍 Project Overview
**YouTube Analysts** is a data analysis project that explores the **most subscribed YouTube channels** using the dataset `most_subscribed_youtube_channels.csv`. The goal is to gain insights into subscriber counts, video views, content categories, and geographical distributions of the most popular YouTube creators.

## 📁 Dataset
**File:** `most_subscribed_youtube_channels.csv`  
This dataset includes details such as:
- Channel name
- Number of subscribers
- Number of videos
- Total views
- Category (e.g., Music, Gaming)
- Country

## 🚀 Features
- Load and clean real-world YouTube channel data
- Perform Exploratory Data Analysis (EDA)
- Visualize top channels by subscriber count, views, and content category
- Identify trends across countries and categories
- Compare subscriber-to-video ratios

## 🛠️ Technologies Used
- **Python 3**
- **Jupyter Notebook**
- **Pandas** – Data loading & manipulation
- **Matplotlib** & **Seaborn** – Data visualization

## 📦 Installation & Usage
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/youtube-analysts.git
   cd youtube-analysts
   ```

2. **Install required libraries**
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook youtube_analysts.ipynb
   ```

4. **Dataset location**
   Place the `most_subscribed_youtube_channels.csv` inside a `data/` directory:
   ```
   youtube-analysts/
   ├── youtube_analysts.ipynb
   ├── data/
   │   └── most_subscribed_youtube_channels.csv
   └── README.md
   ```

## 📊 Example Analyses
- 🔝 Top 10 most subscribed YouTube channels
- 🌍 Distribution of top channels by country
- 🎭 Dominant content categories among top channels
- 📈 Relationship between views, subscribers, and video count

## 📌 Future Enhancements
- Time-series analysis for subscriber growth trends
- Interactive dashboard using Streamlit
- Integration with the YouTube Data API for live data

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

