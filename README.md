## LLMs And Knowledge Graphs

In recent years, significant advancements in artificial intelligence (AI) have expedited the development of large language models and knowledge graphs, revolutionizing how we process and understand information.

Large language models have demonstrated exceptional capabilities in generating human-like text and performing various language-related tasks. On the other hand, knowledge graphs have emerged as powerful tools for organizing and representing structured knowledge, enabling efficient data retrieval and inference. Both these technologies have demonstrated immense potential in isolation, but the true transformative power lies in their integration.

The unification of large language models and knowledge graphs presents a compelling opportunity to enhance the capabilities and intelligence of AI systems. Combining the generative power of large language models with the semantic richness and structured representation of knowledge graphs can build more context-aware, accurate, and explainable AI systems that revolutionize how we interact with and leverage information.

There are different approaches to unify large language models and knowledge graphs:

<p align="center">
<img src="https://github.com/ra9hur/LLMs-And-Knowledge-Graphs/assets/17127066/aaae0fa4-55c7-438f-9869-bbea6260cc59" alt="image" width="1000" height="auto">
</p>


Here, you would see KG-enhanced-LLMs being explored.

<p align="center">
<img src="https://github.com/ra9hur/LLMs-And-Knowledge-Graphs/assets/17127066/f8295698-5ee7-46f7-a715-e30a81dcf061" alt="image" width="800" height="auto">
</p>


## Required Installations And Packages
- Install Neo4j locally OR create a login for sandbox access
- LangChain
- Ollama for open-source LLM
- Streamlit


## How to go about

If you are new to knowledge graphs, suggest to check primer notebooks and then move further to the stack overflow related prototype.

1. Start Neo4j and Ollama services
2. Update .env for environment variables
3. Create a blank project on Neo4j
3. Run loader.py through Streamlit. This pulls top posts from Stack Overflow corresponding to the "Neo4j" tag and creates a knowledge graph.
4. Run bot.py through Streamlit. Here you get an option to use knowledge graph as RAG and post related queries to the LLM assistant.


## References
1. [RAG with a Neo4j Knowledge Graph: How it Works and How to Set It Up](https://www.youtube.com/watch?v=ftlZ0oeXYRE)
2. [neo4j for Data Scientists playlist](https://www.youtube.com/playlist?list=PLreVlKwe2Z0Sf3lEsAJ0E7kv60vdhnUR7)
3. [Knowledge Graphs & LLMs: Harnessing Large Language Models with Neo4j](https://medium.com/neo4j/harnessing-large-language-models-with-neo4j-306ccbdd2867)
