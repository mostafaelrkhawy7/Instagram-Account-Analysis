# Instagram account Performance Analysis

## 1. Project Overview

This project presents an in-depth analysis of an Instagram account's performance. By leveraging Python and data analysis techniques, this study dives into key engagement metrics to uncover patterns, understand audience behavior, and identify the primary drivers of content reach and interaction. The goal is to move beyond surface-level metrics and provide actionable insights for a more effective content strategy.

---

## 2. Problem Statement & Objectives

The primary objective of this analysis is to understand the factors that contribute to high engagement and reach on Instagram. To achieve this, the project aims to answer the following key questions:
* What is the relationship between different engagement metrics (Likes, Comments, Shares, Saves)?
* How does the source of traffic (e.g., Home, Hashtags, Explore) impact post performance?
* Does the length of the caption or the number of hashtags influence engagement and impressions?
* Which types of posts generate the most interaction and are most likely to be saved or shared?

---

## 3. Dataset

The dataset used for this analysis contains performance metrics for a collection of Instagram posts. Each record includes information such as the number of Likes, Comments, Shares, Saves, Impressions, and the source from which the impressions were generated (e.g., Home, Explore, Profile, Hashtags).

---

## 4. Tools and Libraries

* **Language:** Python
* **Libraries:**
    * **Pandas:** For data manipulation, cleaning, and analysis.
    * **Plotly & Seaborn:** For creating interactive and insightful data visualizations.
    * **Jupyter Notebook:** As the environment for conducting the analysis.

---

## 5. Analysis Process

The project follows a structured data analysis workflow:

1.  **Data Wrangling:**
    * **Assessing:** Initial inspection of the dataset to identify quality issues such as duplicates, and incorrect data types.
    * **Cleaning:** Handling the identified issues to ensure the data is accurate and ready for analysis.
2.  **Feature Engineering:**
    * Creating new, insightful features from existing data, such as `Engagement_Rate`, to deepen the analysis.
3.  **Exploratory Data Analysis (EDA):**
    * Utilizing statistical summaries and visualizations to explore relationships between variables, identify trends, and uncover patterns in the data.
4.  **Drawing Conclusions:**
    * Synthesizing the findings from the EDA to answer the initial questions and formulate data-driven recommendations.

---

## 6. Conclusion & Recommendations

 **Top Performing Posts**  
   - Posts with the highest **likes, shares, and impressions** were mostly discovered through the **Explore feed**.  
   - Posts that brought the most **new followers** were discovered primarily through **Hashtags**.  
   - Saves were strongest when impressions came from **Home** and **Hashtags**, showing that loyal followers contribute significantly to deeper engagement.  

2. **Sources of Impressions**  
   - **Home** and **Hashtags** generated the highest number of impressions overall.  
   - However, **Explore** posts drove the **strongest engagement and profile visits**, making Explore a key source for discovery and interaction.  
   - **Hashtags** were the most effective source for driving **profile visits**, while **Home** and **Explore** were the strongest for driving **engagements**.  

3. **Relationships Between Metrics**  
   - **Likes** had the strongest impact on **Impressions**. There was a strong positive correlation between likes and impressions, followed closely by **Saves** and **Followers**.  
   - **Shares** showed a moderate to strong positive relationship with impressions, and were also strongly related to Saves (0.87), Likes (0.72), and Follows (0.52).  
   - **Saves** were highly connected to other metrics: strong positive correlations with Shares (0.87), Likes (0.84), and Follows (0.65).  
   - **Comments**, however, showed weak or no correlation with most metrics, meaning they are less reliable indicators of post success compared to Saves, Likes, or Shares.  

4. **Impact of Content Features**  
   - **Hashtag Count**: More hashtags did not guarantee higher performance. In fact, the correlation with impressions (-0.29) and likes (-0.33) was weak to moderately negative, suggesting that excessive hashtags may reduce engagement.  
   - **Caption Length**: There was almost no meaningful relationship between caption length and impressions (-0.091) or likes (-0.14). Longer captions did not necessarily increase visibility or engagement.  

---

## 7. Key Results & Findings
**Key Business Insights**  
   - Focus on optimizing content for **Explore** and **Home** feeds, as they are the biggest drivers of impressions and engagement.  
   - Develop a **smart hashtag strategy**: too many hashtags can actually reduce likes and impressions. A smaller, targeted set of hashtags is more effective.  
   - Prioritize **Likes, Saves, and Shares** as the main KPIs — these metrics are highly correlated and directly tied to visibility and growth.  
   - Comments should not be the sole measure of engagement, as they provide weaker insights compared to other actions.  

---

💡 **Final Thought**: Sustainable growth on Instagram comes from a balance between **discoverability** (through Explore and effective hashtag use) and **quality engagement** (Likes, Saves, Shares). By prioritizing these areas, an account can maximize both reach and meaningful user interaction.  


---

## 8. How to Run the Project

1.  Clone the repository:
    ```bash
    git clone https://github.com/mostafaelrkhawy7/Instagram-Account-Analysis.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd your-Instagram-Account-Analysis
    ```
3.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
4.  Open and run the `Instagram Account-Analysis Project.ipynb` file in Jupyter Notebook or JupyterLab.
