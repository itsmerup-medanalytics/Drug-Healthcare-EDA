# Drug & Healthcare Data Analysis

# Project Overview

This project performs exploratory data analysis on drug-related healthcare data, examining drug names, medical conditions, therapeutic drug classes, prescription classification (Rx/OTC), ratings, review counts, pregnancy categories, and alcohol interaction. The analysis integrates patient satisfaction metrics with structured clinical safety indicators to ensure reliable drug comparison.

# Analysis Performed

- Cleaned dataset by removing unnecessary columns and handling missing values.
- Applied review threshold filtering (≥100 reviews) to reduce small-sample bias.
- Analyzed rating distribution and review count distribution.
- Identified top and least rated drugs based on reliable review volume.
- Evaluated medical condition frequency and drug class distribution.
- Compared pregnancy categories to identify safer (A & B) and higher-risk (D & X) drugs.
- Analyzed alcohol interaction classifications and their relationship with reviews.

# Key Insights
 
- Certain medical conditions have significantly more drug options available, indicating higher treatment demand and broader therapeutic research focus, while some conditions have limited drug alternatives.
- Top 10 highest-rated and most-reviewed drugs were identified, along with the 10 lowest-rated drugs, showing user preferences and satisfaction levels.
- the top 10 safest and 10 riskiest drugs for pregnancy were identified based on ratings and reviews.
- Prescription (Rx) drugs are more numerous than over-the-counter (OTC) drugs, reflecting greater reliance on prescribed medications.
- The top 10 reported side effects were identified, providing insight into common adverse reactions.
- Among drug classes, the top 10 with the highest drug counts were highlighted, showing the most represented therapeutic areas.
- Alcohol interaction analysis based on reviews revealed drugs with significant interaction concerns.

# Tools & Technologies Used
- Python (Pandas, NumPy, Matplotlib)
- GitHub (Version Control & Documentation)
- Tableau (Data Visualization & Dashboarding)

# Conclusion
-The analysis demonstrated that drug comparison becomes more reliable when review thresholds are applied, reducing small-sample bias in rating evaluation. It also highlighted that clinical safety classifications do not always align with patient satisfaction scores, emphasizing the importance of evaluating drugs using both experiential and regulatory perspectives.
-Additionally, distribution analysis of medical conditions and drug classes revealed therapeutic concentration in specific areas such as upper respiratory categories, indicating varying levels of treatment diversity across conditions.
-Overall, this study reinforces the importance of combining structured clinical risk classifications with user feedback data to generate meaningful, balanced, and responsible healthcare insights.


