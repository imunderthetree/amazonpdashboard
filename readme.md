# Amazon Prime Video Content Analysis 📺

A comprehensive data analysis project exploring Amazon Prime Video's content catalog, revealing insights about streaming patterns, content strategies, and global distribution trends.

## 🎯 Project Overview

This project analyzes Amazon Prime Video's extensive content library to understand:
- Content distribution patterns across genres, countries, and time periods
- Seasonal trends in content releases
- Evolution of the platform's content strategy
- Geographic and demographic targeting insights
- Director and genre relationship networks

## 📊 Dataset

**Source**: [Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows) - Kaggle Dataset  
**Size**: 9,668+ titles covering movies and TV shows available on Amazon Prime Video  
**Key Features**:
- Title information and descriptions
- Release years and addition dates
- Genre classifications (multi-label)
- Geographic origin data (190+ countries)
- Director and cast information
- Content ratings and duration metrics

## 🛠️ Technologies Used

- **Python 3.11+**
- **Data Processing**: pandas, numpy
- **Visualization**: matplotlib, seaborn, plotly
- **Statistical Analysis**: scipy
- **Network Analysis**: networkx
- **Data Source**: kagglehub

## 📈 Key Analyses Performed

### 1. Content Distribution Analysis
- **Content Type Split**: Movies vs TV Shows ratio analysis
- **Genre Popularity**: Top 15 genres with popularity metrics
- **Geographic Distribution**: Content origin mapping across countries
- **Rating Analysis**: Content rating distribution patterns

### 2. Temporal Pattern Analysis
- **Seasonal Trends**: Content addition patterns by season and month
- **Release Timeline**: Historical content release patterns
- **Content Age Distribution**: Analysis of how fresh vs vintage content performs
- **Platform Evolution**: Genre diversity growth over time

### 3. Advanced Statistical Insights
- **Correlation Analysis**: Relationships between numeric variables
- **Hypothesis Testing**: Statistical comparison of movies vs TV shows
- **Genre Momentum**: Growth rate analysis for different genres
- **Content Freshness**: Platform strategy evolution tracking

### 4. Interactive Visualizations
- **Animated Genre Evolution**: Time-series analysis of genre popularity
- **Geographic Heat Maps**: Country-wise content distribution
- **Sankey Flow Diagrams**: Content flow from country → genre → type
- **Sunburst Charts**: Hierarchical content categorization
- **Multi-dimensional Dashboard**: Comprehensive overview with multiple chart types

### 5. Network and Relationship Analysis
- **Director-Genre Networks**: Connections between prolific directors and genres
- **Multi-label Genre Analysis**: Genre combination patterns
- **Content Strategy Insights**: International vs domestic content ratios

## 🔍 Key Findings

### Content Strategy Insights
- **Diversification**: Amazon Prime shows increasing genre diversity over time
- **Global Expansion**: Strong international content acquisition strategy
- **Seasonal Patterns**: Distinct seasonal preferences for different content types
- **Content Age**: Strategic mix of fresh releases and classic content

### Geographic Insights
- **Market Focus**: Strong presence in key markets with localized content
- **International Growth**: Expanding content from diverse geographic origins
- **Cultural Adaptation**: Genre preferences vary by region and season

### Temporal Insights
- **Release Timing**: Strategic content drops aligned with viewing patterns
- **Platform Maturity**: Evolution from broad content to niche specialization
- **Trend Adaptation**: Quick response to emerging genre trends

## 📋 Code Structure

```
Amazon Prime Analysis/
│
├── Data Loading & Preprocessing
│   ├── Dataset download via kagglehub
│   ├── Data cleaning and type conversion
│   ├── Feature engineering (seasons, age categories)
│   └── Multi-label processing (genres, countries)
│
├── Exploratory Data Analysis
│   ├── Statistical summaries
│   ├── Distribution analysis
│   ├── Missing data assessment
│   └── Basic visualizations
│
├── Advanced Analytics
│   ├── Correlation analysis
│   ├── Hypothesis testing
│   ├── Trend analysis
│   └── Network analysis
│
└── Interactive Visualizations
    ├── Plotly dashboards
    ├── Animated charts
    ├── Geographic maps
    └── Flow diagrams
```

## 🚀 How to Run

1. **Install Dependencies**
   ```bash
   pip install kagglehub pandas numpy matplotlib seaborn plotly networkx scipy
   ```

2. **Run the Analysis**
   ```bash
   jupyter notebook Amazon.ipynb
   ```

3. **View Results**
   - Static plots will display inline
   - Interactive visualizations will open in your browser
   - Statistical results will be printed to console

## 📊 Output Highlights

### Static Visualizations
- Multi-panel overview dashboard (8 subplots)
- Correlation heatmaps
- Distribution histograms
- Seasonal and temporal patterns

### Interactive Features
- **Dot Charts**: Country-year content additions
- **Sunburst Diagrams**: Hierarchical content exploration
- **Sankey Diagrams**: Content flow visualization
- **Animated Bar Charts**: Genre evolution over time
- **Geographic Choropleth**: Global content distribution
- **Test Dashboard**: Multi-subplot interactive dashboard with geographic maps, polar charts, and bar visualizations


## 🤝 Contributing

Feel free to contribute by:
- Adding new analysis dimensions
- Improving visualization aesthetics
- Extending statistical methods
- Adding predictive modeling components

## 📄 License

This project is for educational and analytical purposes. Dataset rights belong to the original providers.

---

**Note**: This analysis provides insights into Amazon Prime Video's content strategy and patterns. All findings are based on publicly available data and are intended for educational purposes.

