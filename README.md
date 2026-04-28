
# PLAY STORE UNCOVERED: WHAT THE DATA REALLY SAYS
### *Decoding What Makes an App Succeed on Google Play*

  *10,354 apps. 33 categories. 119 genres. One deep analysis.*

---

###  ABOUT THE PROJECT

Ever wondered why some apps skyrocket to millions of downloads while others vanish into obscurity? This project cracks open the Google Play Store dataset and answers that question — with data, visuals, and real insights.

 **Data Source:** [Google Play Store Dataset — Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps?authuser=0)

---

###  WHAT I DID — STEP BY STEP

- **LOADED & EXPLORED THE DATA**
    - Imported ~10,354 app records using Pandas
    - Used `.head()`, `.info()`, `.describe()` to understand structure and spot anomalies early

-  **HUNTED DOWN MISSING VALUES**
     - Found 5 columns with missing data — Rating alone had **1,474 missing entries**
     - Filled numerical gaps with **median values** to avoid skewing the analysis

- **CLEANED THE MESS**
   - Stripped `+` signs from install counts and `$` from price columns
   - Fixed data types so numbers actually behaved like numbers

- **FILTERED & SLICED THE DATA**
  - Isolated **free apps with ratings above 4.5** for focused analysis
  - Performed column-level selections to zoom into what matters

- **EXPLORED DISTRIBUTIONS & RELATIONSHIPS**
  - Analyzed ratings, installs, reviews, price, and size individually
  - Compared **free vs. paid apps** across every key dimension

- **BUILT RICH VISUALIZATIONS**
  - Histplots, Barplots, Boxplots, Countplots, Scatterplots, Heatmaps & Pie Charts
  - Every chart tells a story — nothing is just decoration

- **RAN CORRELATION ANALYSIS**
  - Built full and focused heatmaps to measure what truly drives installs and ratings

---

###   KEY INSIGHTS — WHAT THE DATA REVEALED

|  Finding |  Insight |
|---|---|
|  Most dominant category | **FAMILY (~18%)**, followed by GAME & TOOLS |
|  Free vs Paid split     | **~93% of apps are FREE** — paid apps are a tiny minority |
|  Rating sweet spot  | Most apps cluster between **4.0 – 4.5** |
|  Strongest correlation | **Reviews ↔ Installs (~0.6+)** — more reviews = more downloads |
|  Rating myth busted | **High rating ≠ high installs** — marketing matters more |
|  Size doesn't matter | App size has **zero effect on ratings** |
|  Update frequency wins | Apps updated in **2018 had significantly more installs** |
|  Pricing penalty | **Higher price = fewer installs** — negative correlation confirmed |
|  Audience dominance | **"Everyone" content rating = ~80%** of all apps |
|  Install inequality | Most apps have near-zero installs — a tiny few have **billions** |

---

###  VISUALIZATION HIGHLIGHTS

| Chart Type | Best Insight Shown |
|---|---|
|  Histplot | Skewed distributions in Installs & Reviews |
|  Boxplot | Extreme outliers in Price & Installs |
|  Scatterplot | Reviews strongly relate to Installs |
|  Heatmap | Reviews–Installs strongest correlation |
|  Pie Chart | Free vs Paid split — instantly striking |
|  Countplot | FAMILY dominates categories, Free dominates Type |

---
