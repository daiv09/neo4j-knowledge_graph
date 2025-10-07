# ⚡ Neo4j Knowledge Graph — GraphRAG on Harry Potter Dataset  

### 🧠 Explore, Visualize, and Query Magical Connections using Knowledge Graphs + Neo4j  

---

## 📘 Overview  

This project is a hands-on implementation of **Knowledge Graphs** using **Neo4j** — inspired by **GraphRAG (Graph-based Retrieval-Augmented Generation)**.  
The goal was to understand how real-world entities and their relationships can be represented, queried, and leveraged to make data **more interpretable and context-aware**.

The dataset used here is based on **Harry Potter characters**, their **houses, loyalties, and traits**, visualized and queried through **Neo4j’s Property Graph Model**.

---

## ✨ Features  

- 📂 **Harry Potter Knowledge Graph** built from a structured CSV dataset  
- 🧩 **Nodes** represent entities (People, Houses, Organizations, etc.)  
- 🔗 **Relationships** connect entities — e.g.  
  - `Sirius Black → BELONGS_TO → Gryffindor`  
  - `Sirius Black → LOYAL_TO → Order of the Phoenix`  
- 🧠 Integrated with **LangChain** for Graph-based RAG (GraphRAG)  
- 🧮 Execute **Cypher queries** to traverse and analyze relationships  
- 🧰 Notebook (`graphRAG.ipynb`) demonstrating step-by-step implementation  

---

## 🧱 Tech Stack  

| Component | Description |
|------------|-------------|
| 🐍 Python | Implementation language |
| 🧠 LangChain | LLM + Graph reasoning |
| 🕸️ Neo4j | Graph database for storing and querying data |
| 📄 Kaggle Dataset | Harry Potter characters dataset |
| 🧩 Cypher Query Language | For graph traversal and relationship querying |

---

## 📊 Graph Structure  

Each entity is represented as a **node**, and relationships define the **semantic links** between them.  


Example:  
`Sirius Black → BELONGS_TO → Gryffindor`  
`Sirius Black → LOYAL_TO → Order of the Phoenix`

---

## 🚀 How to Use  

1. Clone the repository  
   ```bash
   git clone https://github.com/daiv09/neo4j-knowledge_graph.git
   cd neo4j-knowledge_graph

2. Open and run the notebook
   ```bash
   jupyter notebook graphRAG.ipynb

3. Upload the dataset `Characters.csv` if needed
4. Connect your Neo4j instance and execute the Cypher queries

🧩 Resources

📘 Notion Notes (Concepts + Visuals): [View Notes](GraphRAG%20neo4j-Notion%20Notes.md)

📹 Reference Video by Krish Naik: [YouTube - Knowledge Graphs Explained](https://youtu.be/hsOJhs3_UCM?si=znqNA7YfG_UXmChF)

💡 Learnings
- Understanding Knowledge Graphs and how they differ from traditional RDBMS
- Building semantic relationships using Neo4j Property Graph Model
- Integrating Graph-based Retrieval-Augmented Generation (GraphRAG)
- Traversing data using Cypher queries
- Visualizing entity connections in an intuitive, interpretable way
