# BADS7201 Social Network Analysis - Food Ingredients
[![](https://img.shields.io/badge/-Knowledge--Graph-blueviolet)](#) 
[![](https://img.shields.io/badge/-Node--Embeeding-blueviolet)](#) 
[![](https://img.shields.io/badge/-K--Mean-orange)](#) 
[![](https://img.shields.io/badge/-Classification-orange)](#)
[![](https://img.shields.io/badge/-Python-brightgreen)](#)

Graphs are a general language for describing and analyzing entities with relations/interactions.

### Databased

Our data is stored in csv format with 2 columns: **Food** and **Ingredients**.

### Knowledge Graph

- Node  : Food , Ingredient

- Edge  : HasIngredients

![alt text](https://github.com/0xNK4141/BADS7201-Social-Network-Analysis/blob/main/Food-Knowledge-Graph.jpg)

### Recomedation

Using node similarity on food and ingredient to create recmmoendation system

```python
recommend = nx.simrank_similarity(G , 'items')
```

### Knowledge Graph - Using Gephi to analyze and visualize

- Node  : Food , Ingredient

- Edge  : HasIngredients

![alt text](https://github.com/0xNK4141/BADS7201-Social-Network-Analysis/blob/main/Food-Ingredients-Network.jpg)

### Node Embeeding and Node Clustering

After the process of embedding the nodes, use KMeans to specify the appropriate number of clusters.

Number of Clusters  : 4

- Cluster 0: Spicys are the main ingredients
- Cluster 1: Fruits are the main ingredients
- Cluster 2: Sweeties are the main ingredients
- Cluster 3: Meats are the main ingredients

![alt text](https://github.com/0xNK4141/BADS7201-Social-Network-Analysis/blob/main/Food-Clustering.jpg)

