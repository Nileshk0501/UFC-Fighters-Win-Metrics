# In the Octagon: UFC Fighters' Age and Performance Metrics

This project provides an in-depth statistical analysis of UFC fighter data to uncover insights related to age, performance metrics, and fight outcomes. Using a dataset comprising over 13,000 UFC fights spanning nearly three decades, the project focuses on identifying key factors that influence fight results. Specifically, the project aims to evaluate the impact of various fighter characteristics, such as age, reach, stance, and aggression, on their performance.

**Note: Course Project for Behavioural Research Statistical Methods for Spring 2024**

## Objectives
The core objectives of this analysis include testing several hypotheses about UFC fighters' win metrics. These hypotheses investigate the relationship between fighter attributes (like reach, stance, and age) and their likelihood of winning. We analyzed whether reach gives fighters a competitive advantage, how stance influences fight outcomes, and whether older fighters tend to prefer certain techniques, such as head strikes, more than younger fighters.

## Data Preprocessing
The original dataset, containing over 500 features and 13,000+ entries, was cleaned and reduced to 34 essential features to meet the scope of our analysis. We handled missing values and scaled the data to focus on fights with complete information. Data cleaning and preprocessing were performed using **Pandas**, ensuring the dataset was ready for statistical testing and visualization.

## Statistical Testing
We used several statistical methods to test hypotheses:
- **Logistic Regression**: Applied to test the influence of head strike defense on fight outcomes.
- **Chi-Square Tests**: Used to analyze categorical relationships, such as the influence of a fighter’s stance on their win rate and the connection between method of victory and division.
- **Mann-Whitney U test**: Conducted to compare preferences for head strikes between older and younger winning fighters.

## Visualizations
Data visualization played a crucial role in presenting the results of the analysis. Using **Matplotlib** and **Seaborn**, we created histograms, heatmaps, and correlation matrices to visualize the relationships between variables, such as reach differences, stance frequencies, and victory methods across divisions.

## Tech Stack
- **Language**: Python
- **Libraries**: Pandas, SciPy, Statsmodels
- **Visualization**: Matplotlib, Seaborn
