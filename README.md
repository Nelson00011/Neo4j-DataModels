<h1 align="center">Neo4j: Architecting a Scalable Graph Layer on Databricks</h1>

<p align="center"><a href="https://www.bigmarker.com/neo4j/the-foundation-architecting-a-scalable-graph-layer-on-databricks?bmid=abd4eb06bbf5"><img src="Neo4j-DataModels-Images.jpg"></img></a></p>

## Description:
**The Foundation: Architecting a Scalable Graph Layer on Databricks** 
Graphs are critical for understanding complex relationships, but building one from a Lakehouse requires more than just a script. In this session, we show how to architect a scalable graph layer using the Neo4j Spark Connector. Using a financial fraud use case, we demonstrate how to transform Databricks Bronze and Silver tables into a high-performance Neo4j graph model, setting the foundation for advanced analytics, feature engineering, and downstream AI workloads

## Notes:
#### Ryan Knight | [Neo4j](https://www.linkedin.com/in/ryanknight/)
- Sr Partner Architect, Neo4j
- Node Counts match source row counts. Relationship counts fall within expected, range for transaction volume. High-connectivity nodes reflect known patterns from source data. 
- Cycle Detection: fraud ring flags in the alerts table. pageRank: risk scores for investigation prioritization. 
- Community Detection: fraud ring groupings via Louvain.
- Degree Centrality: counterpart counts as ML Features
- Hallucination: plausible answers with no grounding in your data
- An LLM reads each chunks and extracts entities: regulations, thresholds, procedures
- GraphRAG: Graph-Enriched Retrieval. GraphRAG reaches graph data: grounded answers with entities and relatoinships from the konwledge graph
- Lakehouse holds the rest: transactions volumes, aggregations, trends in Delta Tables
- GraphRag can't computer SQL
- Context Window pollution: two schemas, two query languages, and two sets of conventions in one prompt dilutes focus
- Narrow Scope: an agent that only knows about graph strucutre writes graph queries; an agent that knows about both starts mixing them up
- Different reasoning patterns: SQL thinks in rows, filter, and aggregations: 
Cypher thinks in paths, patterns and tranversals
- Reliability: a generalist agent produces queirst that mix idioms. 


#### Will Jeffery | [Neo4j](https://www.linkedin.com/in/william-jeffery-2b010561/)
- Sr Solution Architect, Databricks

#### Shyam Kathiresan | [Neo4j](https://www.linkedin.com/in/shyam-kathiresan-7964571/)
- Global Cloud Partnership Director

## Upcoming Events:
- WEBINAR 2 — [Enrichment](https://go.neo4j.com/WBR-EDU-260312-Graph-Intelligence-on-Databricks-Webinar-Series_01.Registration.html)
    - Graph-Augmented Intelligence: Feature Engineering with Neo4j and Databricks
- WEBINAR 3 — [The AI Agent](https://go.neo4j.com/WBR-EDU-260312-Graph-Intelligence-on-Databricks-Webinar-Series_01.Registration.html)
    - Agentic GraphRAG: Orchestrating Neo4j Context via Databricks and MCP


## Resources:
- Neo4 has a document overview for [Cypher](https://neo4j.com/docs/cypher-manual/current/introduction/cypher-overview/):
    - **Cypher®** is Neo4j’s declarative graph query language. Graph Connectors and Integrations [here](https://neo4j.com/product/connectors/?utm_source=GSearch&utm_medium=PaidSearch&utm_campaign=CTAMER_CRSearch_SRNAWest_Non-Brand_DSA&utm_content=PCCoreDB_SCAura_Product&utm_term=&gad_source=1&gad_campaignid=20973570604&gbraid=0AAAAADk9OYru0-tsthdDN5YKtZiLRM8GK&gclid=CjwKCAjwyMnNBhBNEiwA-KcguzXD2M5NcFVn2WTOV6soHU-nlB8pECWDf_dhJUXCpJCOxN7efgxwHxoCzZwQAvD_BwE).

    - Intelligence platform: 
        - Data Layer:  is a structured, often JavaScript-based, repository used to collect, store, and share information between a website/app and third-party tools like analytics or marketing platforms
        - Knowledge Layer: is a unified, metadata-driven architectural layer that sits between raw data sources (databases, documents) and AI applications or business users
        - Retrieval Layer: in AI (specifically within Retrieval-Augmented Generation or RAG) is the specialized, intermediate component of a system that fetches relevant, up-to-date, or proprietary data from external sources and feeds it to a Large Language Model (LLM) before a response is generated
        - Agent Layer: is a functional component within the AI application stack that houses individual, specialized AI agents designed to execute specific tasks

## Contact:
<!--- You can add in your linkedin, medium, stack overflow, dev.to account, etc. here --->
If you want to contact me you can reach me at <nelson@oakhalo.com>.

Connect with me on <a href="https://www.linkedin.com/in/ayla-nelson/">LinkedIn</a>

Connect with me on <a href="https://github.com/oakHalo">Oakhalo.dev</a>

<!-- 
### TODO stx: 
Future Structure (stx):
backend
frontend
images
screenShots [contains video link]
troubleShooting [contains issues resolved]
-->
