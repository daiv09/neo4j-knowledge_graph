# GraphRAG & Neo4j – Knowledge Graph Notes

## What is a Knowledge Graph?
- **Semantic network**: Connects real-world entities (people, places, concepts, etc.)
- **Relationships**: Illustrates how entities relate
- **Examples**:
  - New Delhi —[is capital of]→ India
  - Berlin —[is capital of]→ Germany

## Knowledge Graph Components
- **Nodes**: Entities in a domain (e.g., cities, countries, events)
- **Relationships**: Edges connecting nodes, showing how entities relate
- **Labels (optional)**: Define node types (e.g., `City`, `Country`)

![Knowledge Graph Example](https://ik.imagekit.io/kqmrslzuq/Github_README/image_1_2.png?updatedAt=1761235012609)

---

## Named Entity Recognition (NER) in NLP
- **Purpose**: Identify and categorize important information (entities) from text
- **Entities**: People, organizations, locations, dates, etc.

---

## Traditional Retrieval-Augmented Generation (RAG)
- **Process**: Combine information retrieval with LLM generation
- **Flow**: User query → Retrieve relevant docs → Generate answer using documents

![Traditional RAG](https://ik.imagekit.io/kqmrslzuq/Github_README/image_1.png?updatedAt=1761235012916)
[Source: Notion](https://www.notion.so)

---

## RDBMS vs Knowledge Graph

| RDBMS         | Knowledge Graph          |
| ------------- | ----------------------- |
| Tables        | Graph                   |
| Insertion of Row  | Insertion of Nodes       |
| Columns/Data  | Properties & Values     |
| Constraints (Keys) | Relationships between nodes |

---

# Neo4j – Overview & Property Graph Model

- **Real-time insights**
- **Easy data retrieval** via Cypher Query Language
- **Cypher**: Declarative, visual graph query language
- **No joins** or nested queries

## Neo4j Property Graph Data Model

- **Nodes**: Represent real-world entities
- **Relationships**: Directed connections (uni-/bi-directional)
- **Properties**: Key-value pairs on nodes/relationships
- **Labels**: Describe node type/category

**Example Structure**  

NODE: Berlin (Label: City)
└─[isCapitalOf]→ NODE: Germany (Label: Country)


---

**Summary**
- Knowledge graphs = entities + relationships for semantic search/QA
- Neo4j uses nodes, edges, properties, and labels; queried via Cypher
- RAG leverages graphs for better context; NER helps extract entities from text
