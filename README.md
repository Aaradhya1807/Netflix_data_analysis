# 🎬 Netflix Data Analysis (with LLM-Enhanced Insights)

This project is an exploratory data analysis (EDA) of a Netflix dataset using Python.  
It highlights key insights into Netflix’s content catalog including content types, top countries, director and actor popularity, rating distribution, and year-wise content trends.

Additionally, the project integrates **Large Language Models (LLMs)** to automatically generate **natural-language, executive-level insights** from analytical results, enhancing data storytelling.

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

- **Top Countries Analysis**  
  Identified the countries with the most titles available on Netflix.

- **Top Directors & Actors**  
  Extracted and analyzed the most frequently appearing directors and actors by exploding multi-valued columns.

- **Year-wise Content Additions**  
  Extracted `year_added` from the `date_added` column and plotted how Netflix’s content library grew over time.

- **Rating Distribution**  
  Analyzed the distribution of content ratings such as TV-MA, TV-14, PG, etc.

---

## 🤖 LLM Integration (Generative AI)

This project integrates **Large Language Models (LLMs)** to enhance analytical storytelling.

### Key LLM Use Case
- **Auto-Generated Insights**  
  Aggregated analytical results (e.g., top actors, genres, trends) are converted into **clear, professional, executive-level insights** using an LLM.

### How It Works
1. Data is analyzed using Pandas.
2. Key results are converted into structured text.
3. A pre-trained LLM generates human-readable insights from the analysis.
4. Visualizations are created using Matplotlib, while insights are displayed alongside them.

> The LLM is used **only for inference**, not for model training, following industry best practices.

---

## 🛠️ Libraries & Tools Used

- Python 3.x  
- Jupyter Notebook  
- Pandas  
- Seaborn  
- Matplotlib  
- OpenAI API (LLM-based insight generation)  

---

## 🚀 How to Run

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/netflix-data-analysis.git
   cd netflix-data-analysis


2. **Install the required libraries**:
   ```bash
   pip install -r requirements.txt

3. **Set up environment variables:**

    *Create a .env file in the project root

      *Add your API key: OPENAI_API_KEY=your_api_key_here
4. **Open the notebook:**
   ```bash
   jupyter notebook NETFLIX_DATA_ANALYSIS.ipynb


**🔐 Security Note**

API keys are stored securely using environment variables and are excluded from version control via .gitignore.
Any previously exposed keys were revoked to ensure repository security.

## 🔮 Future Improvements
Add deeper genre-level analysis using listed_in

Perform sentiment or thematic analysis on content descriptions using LLMs

Build interactive dashboards using Streamlit or Power BI

Enable natural-language querying over the dataset

Extend LLM usage for automated report generation


## AUTHOR
Aaradhya Maharishi
aaradhyamaharishi18@gmail.com

