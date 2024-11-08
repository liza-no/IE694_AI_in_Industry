# Social Network Analysis for Business Process Management

This Jupyter Notebook explores the use of **Social Network Analysis (SNA)** in **Business Process Management (BPM)**. It was developed as part of a portfolio submission for the course *Industrial Applications of Artificial Intelligence*.

## Overview
The notebook provides an analysis of a loan application process event log from Eindhoven University of Technology (https://data.4tu.nl/articles/_/12689204/1). Using **process mining** and **social network analysis**, the notebook demonstrates how to:
- Extract social networks from event log data
- Visualize network structure and compute basic statistics
- Identify communities or clusters within networks using Louvain algorithm, greedy modularity approach and DBSCAN

## Contents
1. **Introduction**: Background on BPM and SNA
2. **Data Source**: Description of the event log dataset
3. **Modules**: Overview of imported libraries
4. **Social Network Analysis Tools in PM4PY**: SNA methods using PM4PY
5. **Social Network Analysis with NetworkX**: Network visualization and analysis, community detection with Louvain algorithm and greedy modularity
6. **Clustering with DBSCAN**: Community detection with DBSCAN
7. **Conclusions and Future Work**

## Requirements
The notebook uses the following Python libraries:
- `pm4py`
- `networkx`
- `matplotlib`
- `pandas`
- `node2vec`
- `scikit-learn`

Install the required packages with:
```bash
pip install -r requirements.txt
