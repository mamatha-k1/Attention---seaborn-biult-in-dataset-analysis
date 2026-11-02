# Attention Dataset Analysis and Visualization

## Project Overview

# 🧠 Introduction

This project uses the **Seaborn Attention dataset**, which comes from a psychology experiment where participants solved word puzzles (anagrams) under two different conditions:

- **Focused Attention Group 🎓** → participants worked without distractions.  
- **Divided Attention Group 📱** → participants solved puzzles while distracted.  

Each participant attempted the puzzles across multiple trials, and their **scores** were recorded.  
By analyzing these results, we can explore how attention impacts **accuracy, consistency, and overall performance**.


---

## Dataset Information

The Attention dataset contains experimental observations related to human attention levels under different conditions.

### Features

| **Column** | **Meaning** |
| --- | --- |
| **Unnamed: 0** | Index column automatically added when saving/loading the dataset. It’s just a row number, not meaningful for analysis. |
| **subject** | Participant ID — a numeric identifier for each person in the experiment. |
| **attention** | Experimental condition — whether the participant was in the *focused* or *divided* attention group. |
| **solutions** | Trial number — which attempt (1, 2, or 3) the participant was solving an anagram puzzle. |
| **score** | Performance score — number of correct solutions in that trial (continuous numeric values). |

---

## Objectives

- Understand the distribution of attention scores.
- Compare attention scores across different solution conditions.
- Analyze the effect of presentation rates on attention.
- Identify patterns and variations among participants.
- Create informative visualizations for better interpretation.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Analysis Performed

### 1. Data Exploration
- Dataset overview
- Shape and structure inspection
- Descriptive statistics

### 2. Data Visualization

#### Histogram
Visualizes the distribution of attention scores.

#### Box Plot
Compares score variations across solution categories.

#### Violin Plot
Shows score density and distribution patterns.

#### Count Plot
Analyzes observations in each category.

#### Scatter Plot
Explores relationships between variables.

#### Bar Plot
Displays average attention scores by category.

#### Heatmap
Visualizes correlations among numerical features.

#### Pair Plot
Displays relationships and distributions of attention scores across different solution conditions and presentation rates.

#### lmplot (Linear Model Plot)
Visualizes the trend between attention scores and experimental conditions using a fitted regression line.

#### Line Plot
Shows how attention scores vary across different presentation rates and solution categories.

---

# 🎯 Conclusion


- Focus improves both **accuracy** and **consistency**.  
- Divided attention leads to **unreliable performance** and scattered results.  

**Attention is the foundation of reliable performance.  
Focused attention consistently leads to better outcomes across tasks.**


---
