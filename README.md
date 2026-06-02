# Netflix-Movies-Analysis
This project involves exploratory data analysis (EDA) on a Netflix movies dataset to extract meaningful insights about genre distribution, release trends, movie ratings, duration, and more. The analysis is performed using Python libraries like pandas, matplotlib, seaborn, and plotly for interactive visualizations.

---

## 📊 Netflix Movies Analysis ##
A data analysis project focused on exploring and extracting insights from a Netflix movies dataset. This analysis dives into content trends, rating distributions, genre categorizations, and more using Python data science tools.

![Image](https://github.com/user-attachments/assets/ba2bbdf9-8639-42ab-9901-f0273711f8d7)


---


## 🔍 Project Overview ##
This notebook performs exploratory data analysis (EDA) on a dataset containing nearly 10,000 Netflix titles. Key operations include:

1. Data cleaning and preprocessing

2. Handling missing values and outliers

3. Feature transformation (e.g., categorizing vote averages, processing genre information)

4. Visualizations to understand trends in:

    Release years

    Popularity

    Viewer ratings

    Genre distribution

   ---

## 🛠️ Tools & Technologies Used ##
1. Python

2. Pandas – for data manipulation

3. Matplotlib / Seaborn – for data visualization

4. NumPy – for numerical operations

5. Jupyter Notebook – for interactive analysis
   
---

## 📁 Dataset ##
The dataset includes 9 main columns for 9,827 titles, such as:

1. Title, Release_Date, Genre

2. Popularity, Vote_Average, Vote_Count

3. Columns like Poster_Url, Overview, and Original_Language were dropped for being irrelevant to the core analysis.
   
---


## 📈 Key Findings ##
1. Vote_Average was categorized into: popular, average, below_avg, and not_popular for better insights.

2. Genre column had to be cleaned and processed due to comma-separated values and inconsistent spacing.

3. Popularity showed noticeable outliers that were treated or accounted for.

4. Missing or duplicated values were minimal or non-existent, making the dataset relatively clean from the start.
   
---


## 🚀 Getting Started ##
To run this project locally:

sbash
Copy
Edit
git clone https://github.com/Harikesh-Prajapati/netflix-movies-analysis.git
cd netflix-movies-analysis
jupyter notebook


---


## 📌 Future Enhancements ##
Incorporate TV shows data along with movies

Add interactive visualizations with Plotly or Dash

Perform correlation analysis between popularity, genres, and ratings

## 📄 License ##
This project is open-source and available under the MIT License.

---
