# 🎬 Netflix Data Analysis

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of the Netflix dataset using Python.

The objective is to explore Netflix movies and TV shows, understand content distribution, identify popular countries and genres, and analyze movie durations through data visualization.

## 🎯 Objectives

- Analyze the distribution of Movies and TV Shows.
- Explore Netflix content additions over the years.
- Identify the top 10 countries producing Netflix content.
- Discover the most common genres.
- Analyze the distribution of movie durations.
- Handle missing values and prepare data for analysis.

## 🛠️ Technologies & Libraries

- **Python** – Programming language.
- **Pandas** – Data manipulation and cleaning.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Jupyter Notebook** – Development environment.

## 📊 Data Analysis

The project includes the following analyses:

### 1. Data Cleaning
- Loading the Netflix dataset.
- Identifying missing values.
- Handling missing country and director values.
- Removing rows with missing dates and ratings.
- Converting dates into datetime format.
- Extracting the year of content addition.

### 2. Content Distribution
- Comparing Movies and TV Shows.
- Visualizing content distribution using a pie chart.

### 3. Content Over Time
- Analyzing the number of Movies and TV Shows added each year.
- Visualizing trends using a line chart.

### 4. Top 10 Countries
- Identifying the countries with the highest number of Netflix titles.
- Visualizing results using a bar chart.

### 5. Top 10 Genres
- Exploring the most common genres on Netflix.
- Displaying the results using a bar chart.

### 6. Movie Duration Analysis
- Extracting movie durations in minutes.
- Analyzing the distribution of movie lengths using a histogram.

## 📁 Project Structure

```text
Netflix-Data-Analysis/
│
├── Netflix.ipynb
├── netflix_titles.csv
└── README.md
```

## ⚙️ Installation & Usage

**1. Clone the repository**

```bash
git clone https://github.com/USERNAME/Netflix-Data-Analysis.git
```

**2. Navigate to the project folder**

```bash
cd Netflix-Data-Analysis
```

**3. Install the required libraries**

```bash
pip install pandas matplotlib seaborn jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open `Netflix.ipynb` and run the cells.**

Make sure `netflix_titles.csv` is in the same directory as the notebook.

## 📚 Dataset

The project uses the Netflix Movies and TV Shows dataset (`netflix_titles.csv`), containing information such as:

- Show ID
- Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

## 👨‍💻 Author

Mohamed fartat

Computer Science Student | Interested in Data Science & Artificial Intelligence.

---

⭐ If you find this project interesting, feel free to star the repository!
