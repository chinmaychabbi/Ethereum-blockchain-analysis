# Exploring the Ethereum Blockchain Through Network Analysis

##  Overview
This project performs an in-depth **network analysis of the Ethereum blockchain**, focusing on transaction data to understand network structure, key players, and patterns in decentralized finance (DeFi). Using real transaction records from 2018 to 2020, we analyzed how decentralized and centralized exchanges interact, revealing hidden patterns through various network science techniques.

This was completed as part of **CPTS 591: Elements of Network Science** at **Washington State University**.

---

## 🛠 Tools & Technologies
- **Language**: R
- **Libraries**: igraph, dplyr, ggplot2
- **Platform**: RStudio, R Markdown
- **Visualization**: Graph layouts, centrality metrics, community clustering
- **Data Source**: Ethereum Blockchain (via Stanford SNAP)

---

##  Analysis Performed

### 1. **Network Structure Analysis**
- Explored metrics like density, average path length, clustering coefficient, and algebraic connectivity.
- Nodes = Accounts, Edges = Transactions  
- **Total Nodes**: 3,974  
- **Total Edges**: 10,000  
- **Diameter**: 18, **Average Path Length**: 5.35  

### 2. **Centrality / Node Importance**
- Calculated **degree**, **closeness**, **betweenness**, **PageRank**, and **eigenvector centrality**
- Identified influential nodes that play a key role in the transaction network

### 3. **Influence Analysis**
- Simulated influence propagation using eigenvector centrality
- Analyzed high-impact nodes and their transaction behavior over time

### 4. **Community Detection**
- Used **Walktrap algorithm** to identify dense subgraphs (communities)
- **Modularity Score**: 0.74, showing well-defined community structures

### 5. **Network Motifs & Subgraph Analysis**
- Detected recurring patterns like triangles, stars, and T-shapes
- Identified structural motifs that indicate typical transaction behaviors and anomalies

---



##  My Role

I led the full analytical pipeline, including:
- Cleaning and preprocessing blockchain data
- Designing network models using igraph
- Conducting structural and centrality analysis
- Creating plots and visuals
- Documenting insights and presenting findings

---

##  Documentation
-  [Final Report](./report/report.pdf)
-  [Presentation Slides](./ppt/ppt.pptx)

---

##  License
This project is for academic and educational purposes only. Attribution required for reuse. You may optionally include an MIT License.

---

##  Contact
For any questions or collaboration opportunities, feel free to connect via [LinkedIn](https://linkedin.com/in/chinmaychabbi) or GitHub.
