# Resident Evil - Dataset creation & Network Analysis

This repository contains a three notebook pipeline that builds and analyzes a synthetic dataset of the Resident Evil game universe. The final goal of this project is doign a social network analysis of character interactions.

## Notebooks

1. **Data scraping and generation**  
   - Scrapes character, dialogue and scene data from public game transcripts and wiki pages.  
   - Normalizes raw HTML into structured tables.  
   - Mixes scraped data with controlled AI‑generated data.

2. **Dataset demo**  
   - Simple demo dataset to show off the new dataset.

3. **EDA & Social Network Analysis**  
   - Constructs a character co‑occurrence graph from shared scenes.  
   - Computes classic SNA metrics (degree, betweenness, closeness, eigenvector centrality) using NetworkX.  
   - Runs community detection (Louvain) and visualizes clusters.

---

Kaggle notebooks:
- [01 – Data scraping & generation](https://www.kaggle.com/code/tommasofacchin/01-resident-evil-data-scraping-and-generation)
- [02 – Dataset demo](https://www.kaggle.com/code/tommasofacchin/02-resident-evil-dataset-demo)
- [03 – EDA & Social Network Analysis](https://www.kaggle.com/code/tommasofacchin/03-resident-evil-social-network-analysis)
