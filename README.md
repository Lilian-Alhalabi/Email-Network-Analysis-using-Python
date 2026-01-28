# Email Network Analysis using Python

## 📌 Project Overview
This project analyzes a real-world organizational email network using **Python** and **NetworkX**.  
The dataset represents email communications between employees in an organization.

- **Nodes:** 1,005 employees  
- **Edges:** 25,571 email interactions  
- **Graph Type:** Directed Network  

The goal is to understand communication patterns, identify key individuals, and visualize the structure of the network.

---

## 📊 Dataset
- **Source:** SNAP (Stanford Network Analysis Project)
- **File:** `email-Eu-core.mtx`
- **Format:** Matrix Market (.mtx)

### Network Representation
- **Node:** An employee
- **Edge:** An email sent from one employee to another
- **Direction:** Sender → Receiver

---

## 🛠 Tools & Technologies
- Python
- NetworkX
- SciPy
- Matplotlib
- Pandas

---

## 🔍 Analysis Performed

### 1. Degree Centrality
- Measures how active each node is.
- Identifies the most active senders and receivers.

### 2. Betweenness Centrality
- Identifies nodes that act as bridges between different groups.
- Highlights strategic connectors in the organization.

### 3. Network Density
- Measures how connected the network is.
- Indicates overall communication efficiency.

---

## 📈 Visualizations
- Network graph of selected nodes
- Node size and color based on degree centrality
- Bar charts for in-degree vs out-degree
- Histogram of betweenness centrality
- Community detection visualization

---

## 💡 Key Insights
- Identification of top communicators
- Detection of strategic connectors
- Clear visualization of organizational communication structure
- Understanding communication flow efficiency

---
## 👩‍💻 Author

## Lilian Alhalabi

<img width="2020" height="1019" alt="image" src="https://github.com/user-attachments/assets/9a6c4ea2-46c7-4f33-88cc-2bca741a435b" />
