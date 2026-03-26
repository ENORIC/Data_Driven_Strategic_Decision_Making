# Data_Driven_Strategic_Decision_Making
This is the Final project for Data Driven Strategic Decision Making

# The Holy Bible — Character Network Analysis

- Exploring Relationships, Influence & Community in Biblical Scripture
- By- Enosh Paul Niju GH1026595

My initial motivation for this project was just pure curiosity, the simple question being "Could the Holy Bible be viewed as a social network?"

This project is entirely focused on data science and network analysis. One of the best documented collections of named characters in history along with their every interaction is written in the Bible, which is why that persuaded me to select it as my primary dataset.

**This has nothing to do with religion or politics.** 


## Data Source 
- *Dataset:* BibleData by Brady Stephenson 
- *Source:* https://www.kaggle.com/datasets/bradystephenson/bibledata

Only taking six necessary CSV files for the project. This dataset is based on the King James Version Bible (KJV) constituting of 66 books in total. All 6 CSV files are included in the data/ folder of this repo.

## The Objectives are

+ Build a co-occurrence network of biblical characters based on shared verse appearances.
+ Analyse network structure and compare it against random graph models (ER, BA, WS).
+ Identify the most central and influential characters using multiple centrality metrics.
+ Detect communities within the network and explore their Old vs New Testament composition.
+ Simulate information spread using the Linear Threshold Model (LTM)+
+ Test network resilience by removing top nodes and observing structural collapse

*Table of Contents*

- Phase 1 — Network Construction
- Phase 2 — Network Analysis
- Phase 3 — Synthetic Graph Comparison (ER, BA, WS)
- Phase 4 — Best Model Selection
- Phase 5 — Centrality Analysis
- Phase 6 — Diffusion Model (LTM)
- Phase 7 — LTM on the Original Bible Graph

- Curosity Based Research Questions A, B, C, D
+ A. Which centrality metric spreads influence the furthest?
+ B. Do Old Testament characters stick together more than New Testament ones?
+ C. If you removed the most important characters, would the Bible network fall apart?
+ D. Do people from the same tribe actually hang out together?

Tools Used

Python / Jupyter Notebook
NetworkX — graph construction and analysis
Pandas — data loading and preprocessing
Plotly — interactive visualizations
Matplotlib — static plots
