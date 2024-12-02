# Google Play Store Analytics

This project provides valuable insights into app performance, user behavior, and market trends on the Google Play Store. It enables app developers, marketers, and business analysts to make informed decisions, optimize app strategies, and enhance user engagement.

## Project Content

### Features and Highlights
- **Data Loading and Cleaning**  
  - Cleaned Google Play Store data using Python's Pandas library.  
  - Handled missing values, duplicates, and data type inconsistencies to ensure data reliability.

- **Data Transformation**  
  - Created new features such as log-transformed install counts, categorized ratings, and calculated revenue metrics.  
  - Gained deeper insights into app performance.

- **Exploratory Data Analysis (EDA)**  
  - Visualized trends in app categories, ratings, and reviews. 
  - Highlighted top-performing app categories.

- **Sentiment Analysis**  
  - Used NLTK to perform sentiment analysis on user reviews.  
  - Determined sentiment polarity (positive, negative, neutral) and its impact on app metrics.

- **Interactive Visualization**  
  - Built dynamic visualizations with Plotly for better user interaction.  
  - Integrated visualizations into web applications using HTML.

- **Dashboard Creation**  
  - Designed a user-friendly dashboard using Plotly for visualizing key insights.  
  - Enabled interaction with data for actionable insights.

---

## Learning Objectives
- Utilize Python libraries: Pandas, NumPy, Plotly, and Scikit-learn.
- Create interactive visualizations with Plotly.
- Perform sentiment analysis with NLTK.
- Integrate visualizations into web applications with HTML.

---

## Tasks Overview

### Task 1  
**Sentiment Distribution Stacked Bar Chart**  
- Visualize sentiment (positive, neutral, negative) segmented by rating groups (1-2, 3-4, 4-5 stars).  
- Include apps with more than 1,000 reviews, grouped by the top 5 categories.  
- ![Task 1 Output](https://github.com/Bhumigor/Google-Play-Store-Analysis/blob/main/Photos/Task1.png)

### Task 2  
**Grouped Bar Chart**  
- Compare average ratings and total review counts for the top 10 app categories by installs.  
- Filter out categories with an average rating below 4.0, size below 10M, and not updated in January.  
- Works between **10 AM to 5 PM**.
- ![Task 2 Output](https://github.com/Bhumigor/Google-Play-Store-Analysis/blob/main/Photos/Task2.png)

### Task 3  
**Correlation Matrix Heatmap**  
- Generate a heatmap to show the correlation matrix between installs, ratings, and review counts.  
- Filter the data to include only:  
  - Apps updated within the last year.  
  - At least 100,000 installs.  
  - Review counts greater than 1,000.  
  - Genres not starting with characters A, F, E, G, I, or K.  
- Works between **3 PM to 6 PM**.
- ![Task 3 Output](https://github.com/Bhumigor/Google-Play-Store-Analysis/blob/main/Photos/Task3.png)

### Task 4  
**Time Series Line Chart**  
- Show total installs over time, segmented by app category.  
- Highlight areas of significant growth (>20% month-over-month increase).  
- Include apps rated for teens, with names starting with "E", and more than 10,000 installs.  
- Works between **4 PM to 8 PM**.
- ![Task 4 Output](https://github.com/Bhumigor/Google-Play-Store-Analysis/blob/main/Photos/Task4.png)

### Task 5  
**Violin Plot**  
- Visualize rating distributions for app categories with more than 50 apps.  
- Include apps with names containing "C", at least 10 reviews, and ratings below 4.0.  
- Does not work between **6 PM to 11 PM**.
- ![Task 5 Output](https://github.com/Bhumigor/Google-Play-Store-Analysis/blob/main/Photos/Task5.png)

---

## Project Files
- **Code**: Analysis code and data transformations.  
- **HTML File**: Graphs and charts to showcase insights.  
- **Project**: Interactive dashboard with Plotly.  
- **Photos**: Includes visualization images for reference.  

---

## Tech Stack
- **Languages**: Python, HTML
- **Libraries**: Pandas, NumPy, Plotly, Scikit-learn, NLTK 
- **Tools**: Jupyter Notebook, Visual Studio Code  

---

