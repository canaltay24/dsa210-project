# **Indie Game Success Analysis**

## **Project Overview**

This research looks on the factors that make independent games on Steam successful. Player numbers and review scores are important metrics used to evaluate success. The goal of this project is to find patterns and trends in SteamDB data that impact popularity, long-term player retention, and general reception of independent games.\
\
We will investigate whether factors like Early Access, price, update frequency, discounts, and genre have a major impact on an independent game's performance using statistical analysis and data visualization.

## **Objectives**

### **1️⃣ Understand Success Factors**

Analyze how **game attributes** (e.g., Early Access, pricing, updates, and reviews) influence an indie game’s performance.

### **2️⃣ Compare Early Access vs. Full Release Games**

Evaluate whether games that go through **Early Access** perform better than those that release as full versions.

### 3️⃣ Determine Important Factors for Developers

Provide actionable insights for **indie game developers** on strategies to maximize player engagement and positive reception.

Use **data cleaning, exploratory analysis, regression modeling, and hypothesis testing** to interpret real-world gaming trends.

---

## **Motivation**

Understanding what makes an indie game successful is crucial for developers looking to navigate the competitive gaming market. By analyzing player behavior, pricing strategies, and release formats, this project provides valuable insights into the factors that contribute to long-term player engagement and positive reception.

For **indie developers**, this study serves as a guide to making informed decisions about game launches, updates, and pricing. Identifying patterns in player counts and review trends can help developers optimize their strategies, ensuring better engagement and success on platforms like Steam. By identifying trends in player engagement and review scores, developers can make more informed decisions about release strategies, pricing models, and post-launch support.

## **Dataset**

The dataset consists of indie game data collected from **SteamDB**, covering essential variables that contribute to game success.

### **🔹 Features Collected:**

| Feature                          | Description                                                           |
| -------------------------------- | --------------------------------------------------------------------- |
| **Game Name**                    | The title of the game.                                                |
| **Release Date**                 | The official release date on Steam.                                   |
| **Early Access (Yes/No)**        | Whether the game was initially released in Early Access.              |
| **Price (Current & Historical)** | Pricing trends over time.                                             |
| **Discount Frequency & Size**    | Number of discounts and the depth of discount percentages.            |
| **Peak Concurrent Players**      | The highest number of players active at the same time.                |
| **Review Count**                 | The total number of reviews on Steam.                                 |
| **Review Score (%)**             | The percentage of positive reviews.                                   |
| **Genres & Tags**                | The genre and tag classification of the game.                         |
| **Multiplayer (Yes/No)**         | Whether the game supports multiplayer features.                       |
| **DLC & Expansion Packs**        | The number of additional content releases.                            |
| **Update Frequency**             | How often the game receives updates (patches, bug fixes, expansions). |

### **📌 Data Sources:**

- **[SteamDB](https://steamdb.info/)** - Extracting game statistics.
- **Steam Store API** - Gathering additional game metadata.

---

## **Hypothesis**

To understand the factors contributing to the success of indie games, the following hypotheses will be tested:

### **H1: Early Access vs. Full Release Success**

- **H₀ (Null Hypothesis):** There is no significant difference in player count and review scores between Early Access games and Full Release games.
- **Hₐ (Alternative Hypothesis):** Indie games that go through Early Access tend to have **higher player counts and better review scores** than those that launch as full releases.

### **H2: Pricing Impact on Success**

- **H₀:** The price of a game has no correlation with its success.
- **Hₐ:** Lower-priced indie games tend to attract **more players** and receive **higher review scores**.

---

## **Analysis Plan**

### **Data Collection**

- Collect and import game data from **SteamDB** into a structured dataset.
- Ensure data consistency by handling missing values and standardizing formats.
- Categorize game attributes such as **Early Access status, pricing, and genre** for analysis.

### **Visualization**

- Use **scatter plots, bar charts, and correlation heatmaps** to explore relationships between variables.
- Example visualizations include:
  - **Scatter plot** of price vs. peak player count.
  - **Bar chart** comparing review scores for Early Access vs. Full Release games.
  - **Heatmap** showing correlations between different game attributes and success metrics.

### **Hypothesis Testing**

- Test hypotheses such as:
  - **H₀:** Early Access does not significantly impact player count or review scores.
  - **Hₐ:** Early Access games have **higher player counts and better review scores**.
- Conduct **statistical analysis (t-tests, ANOVA, regression models)** to identify key predictors of success.

### **Trend Analysis**

- Investigate long-term trends in indie game performance.
- Compare **player count trends over time** for Early Access vs. Full Release games.
- Analyze how **discount frequency and price changes** affect long-term engagement.

---

---

