# IMDB-Movies-Analysis

# 🎬 Entertainment Industry Analysis

### Uncovering 120+ Years of Content Evolution, Genre Shifts & Audience Behavior

> **What happens when you analyze over a century of entertainment data?**
>
> This project transforms raw IMDb records into a historical map of the entertainment industry, revealing how content production, genre preferences, and audience targeting evolved from the early cinema era to the age of streaming.

---

## 🚀 Why This Project Matters

The entertainment industry has undergone multiple revolutions:

* The rise of Hollywood
* The television boom
* The digital transformation
* The streaming era explosion

But how did these shifts change what gets produced, who it is made for, and what audiences engage with?

This project answers those questions through large-scale data analysis, visualization, and trend discovery using IMDb data spanning more than a century.

---

## 🎯 Business Questions Answered

✔ How has content production changed over time?

✔ When did the industry's largest growth periods occur?

✔ Are Movies still dominant over TV Series?

✔ Which genres gained or lost popularity over the decades?

✔ How has audience targeting evolved?

✔ What type of content attracts the most engagement?

---

## 📊 Dataset

**Source:** IMDb Dataset (Kaggle)

The dataset includes:

* Titles
* Release Years
* Genres
* Ratings
* Vote Counts
* Certifications
* Directors
* Cast Information
* Content Type (Movie / TV Series)

---

# ⚙️ Project Workflow

## 1. Data Acquisition

Loaded and explored raw IMDb datasets containing historical entertainment records.

### Output

* Structured analytical dataset
* Initial quality assessment
* Feature selection

---

## 2. Data Cleaning & Transformation

Raw entertainment data contained inconsistent formats, missing values, and complex text structures.

### Tasks Performed

* Standardized movie titles
* Converted runtimes to numerical values
* Cleaned vote counts
* Removed invalid entries
* Handled missing records

### Tools

* Python
* Pandas
* NumPy

---

## 3. Advanced Temporal Parsing

Entertainment datasets often contain irregular year formats.

Using **Regular Expressions (Regex)**, start and end years were extracted to distinguish:

* Standalone Movies
* Ongoing TV Series
* Multi-Year Productions

This enabled accurate historical trend analysis.

---

## 4. Identity Mapping

Director and actor information was normalized and exported for future analysis.

### Process

* Cleaned Director IDs
* Cleaned Actor IDs
* Managed anonymous entries
* Generated JSON mappings

---

## 5. Exploratory Data Analysis

The project investigates:

### 📈 Production Growth

How content creation expanded across generations.

### 🎥 Movies vs TV Series

A long-term comparison of entertainment formats.

### 🎭 Genre Evolution

Tracking which genres dominated each era.

### 👨‍👩‍👧 Audience Segmentation

Classifying certifications into:

* Kids
* Family
* Adult

### ⭐ Audience Engagement

Measuring viewer interaction through ratings and vote activity.

---

# 📊 Key Insights

## 🚀 The 21st Century Content Explosion

Production volume accelerated dramatically after 2000, reaching unprecedented levels before a visible post-2020 slowdown.

---

## 🎥 Movies Continue to Dominate

Despite rapid TV growth during the Television and Streaming Eras, movies remain the largest content category by total volume.

---

## 🎭 Genre Evolution Never Stopped

Drama and Comedy consistently maintained leadership positions while niche genres expanded significantly during the digital era.

---

## 🔞 Adult Content Experienced Major Growth

Adult-oriented productions increased steadily from the mid-20th century onward and generated substantial audience engagement.

---

## ⭐ Engagement Doesn't Always Follow Volume

Some audience segments produce fewer titles yet generate disproportionately high viewer interaction and voting activity.

---

# 📈 Visual Analytics

This project includes:

* Production Trend Analysis
* Genre Popularity Tracking
* Audience Segmentation Analysis
* Interactive Plotly Dashboards
* Animated Genre Bar Chart Races
* Historical Growth Visualizations

### Example Outputs

```markdown
![Production Trends](visuals/production_trends.png)

![Genre Evolution](visuals/genre_evolution.gif)

![Audience Analysis](visuals/audience_analysis.png)
```

---

# 🛠️ Tech Stack

| Category                | Technology       |
| ----------------------- | ---------------- |
| Programming             | Python           |
| Data Processing         | Pandas           |
| Numerical Analysis      | NumPy            |
| Text Parsing            | Regex            |
| Visualization           | Plotly           |
| Data Storage            | JSON             |
| Development Environment | Jupyter Notebook |

---

# 📂 Project Structure

```text
Entertainment-Industry-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── analysis.ipynb
│
├── visuals/
│   ├── production_trends.png
│   ├── genre_evolution.gif
│   └── audience_analysis.png
│
├── exports/
│   └── director_actor_mapping.json
│
├── README.md
└── requirements.txt
```

---

# 🔮 Future Development

### Machine Learning

Predict IMDb ratings using:

* Genre
* Cast
* Directors
* Runtime

### Financial Analysis

Investigate relationships between:

* Budget
* Revenue
* Genre
* Audience Targeting

### Streaming Era Research

Identify content patterns unique to modern streaming platforms.

### Network Analytics

Visualize actor-director collaboration networks to discover influential industry relationships.

---

# 👨‍💻 About This Project

This project demonstrates practical skills in:

* Data Cleaning
* Data Wrangling
* Feature Engineering
* Exploratory Data Analysis
* Statistical Thinking
* Data Visualization
* Business Insight Generation

The goal was not merely to analyze data, but to transform historical entertainment records into meaningful insights that explain how audience preferences and content strategies evolved over time.

---

### ⭐ If you found this project valuable, consider starring the repository.

**Built with Python, curiosity, and a passion for uncovering stories hidden inside data.**

