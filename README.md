# Social Network Analysis for Business Process Management

This Jupyter Notebook explores the use of **Social Network Analysis (SNA)** in **Business Process Management (BPM)**. It was developed as part of a portfolio submission for the course *Industrial Applications of Artificial Intelligence*.

## Overview
The notebook provides an analysis of a loan application process event log from Eindhoven University of Technology. Using **process mining** and **social network analysis**, the notebook demonstrates how to:
- Extract social networks from event log data
- Visualize network structure and compute basic statistics
- Identify communities or clusters within networks using DBSCAN

## Contents
1. **Introduction**: Background on BPM and SNA
2. **Data Source**: Description of the event log dataset
3. **Modules**: Overview of imported libraries
4. **Social Network Analysis Tools in PM4PY**: SNA methods using PM4PY
5. **Social Network Analysis with NetworkX**: Network visualization and analysis
6. **Clustering with DBSCAN**: Community detection within the network
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
