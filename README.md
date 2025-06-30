# 🎬 Netflix Data Analysis

This project is an exploratory data analysis (EDA) of a Netflix dataset using Python. It highlights key insights into Netflix’s content catalog including content types, top countries, director popularity, and content rating distribution.

---

## 📁 Dataset Overview

The dataset includes details about Netflix titles such as:

- Title  
- Type (Movie or TV Show)  
- Director & Cast  
- Country  
- Date Added  
- Release Year  
- Rating  
- Description

> Source: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 📊 Analyses Performed

- **Null Value Analysis**  
  Visualized missing values using heatmaps and `.isnull().sum()` to understand data completeness.

- **Content Type Distribution**  
  Counted and visualized the number of Movies vs TV Shows using `value_counts()`.

- **Top 5 Countries**  
  Identified the countries with the most titles available on Netflix.

- **Top 5 Directors**  
  Listed the directors with the highest number of titles in the dataset.

- **Year-wise Content Additions**  
  Extracted `year_added` from the `date_added` column and plotted how many titles were added each year.

- **Rating Distribution**  
  Analyzed the distribution of content ratings like TV-MA, TV-14, PG, etc.

---

## 🛠️ Libraries Used

- Python 3.x  
- Jupyter Notebook  
- Pandas  
- Seaborn  
- Matplotlib

---

## 🚀 How to Run

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/netflix-data-analysis.git
   cd netflix-data-analysis

2. **Install the required libraries**:
   ```bash
   pip install -r requirements.txt

3. **Open the notebook:**
   ```bash
   jupyter notebook NETFLIX_DATA_ANALYSIS.ipynb

## 🔮 Future Improvements
Add analysis based on listed_in (genres)

Explore duration data (e.g., movie lengths, TV seasons)

Use Plotly or Streamlit for interactive dashboards

Include popularity or user ratings (if available)


## AUTHOR
Aaradhya Maharishi
maharishiaaradhya@gmail.com

