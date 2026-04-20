---
🌐 Social Network Influence Analysis

##📌 Overview

This project focuses on analyzing a social network to identify influential users using Data Analytics and Graph Theory techniques. By modeling user relationships as a network, the system evaluates influence using advanced algorithms such as PageRank and Centrality Measures.
The project demonstrates how graph-based analytics can help understand information flow, user importance, and network structure, which are critical in domains like social media, marketing, and recommendation systems.
---
🎯 #Objectives
Generate a realistic social network dataset
Construct a directed graph representing user relationships
Apply centrality measures to evaluate node importance
Implement PageRank algorithm for influence ranking
Visualize network structure and insights
Identify top influential users
---
📊 #Dataset
Source: Generated using NetworkX (Barabási–Albert Model)
Nodes (Users): 30
Edges (Connections): ~100
Type: Directed Graph (Follow Relationships)
Features:
Source Node
Target Node
Target:
Influence Score (PageRank / Centrality Values)
---
⚙️#Technologies Used
Python
NetworkX
NumPy
Pandas
Matplotlib
---
🧠 #Algorithms Used
PageRank Algorithm
Degree Centrality
Betweenness Centrality
Closeness Centrality
Eigenvector Centrality
---
📈 #Network Analysis Output
The system generates:
Network statistics (nodes, edges, density)
Centrality scores for each user
PageRank-based influence ranking
Top influential users
---
📊 #Visualizations
The project includes:
Network Graph Visualization
Top Influential Users (Bar Chart)
Centrality Comparison (Scatter Plot)
Radar Chart (Top Users Analysis)
---
🔮 #Sample Output
Top Influential Users:
User 5  → Highest Influence
User 12 → High Influence
User 3  → Moderate Influence
User 8  → Moderate Influence
User 1  → Emerging Influence
---
📁 #Project Structure
├── main.py
├── network_generation.py
├── centrality_analysis.py
├── visualization.py
├── output_graph.png
└── README.md
---
🚀 #How to Run
Install dependencies:
pip install networkx matplotlib numpy pandas
Run the project:
python main.py
Output:
Network statistics
Influence rankings
Graph visualizations
---
🔍 #Key Insights
Influence is not solely based on number of connections
PageRank provides more accurate influence ranking
Some users act as bridges controlling information flow
The network follows a scale-free structure, similar to real-world social networks
---
🔮 #Future Enhancements
Use real-world social media datasets (Twitter, Facebook)
Apply machine learning for influence prediction
Build real-time network analysis system
Develop interactive web/mobile application
Enhance visualization dashboards
---
📚 #References
Python Documentation
NetworkX Documentation
NumPy Documentation
Matplotlib Documentation
Research Papers on Social Network Analysis
---
👨‍💻 Author

**Chandru Sridevi**
