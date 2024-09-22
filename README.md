# Automation on Government Documents: Insights Extraction, Comparison, and Summarization System

## Problem Statement
Develop an automated system for extracting, comparing, and summarizing information from Indian government finance minister budget speeches from 2021 to 2024 .The system should retrieve data from the following URLs:

- https://sansad.in/ls/knowledge-centre/speeches

The system should be capable of:
1. **Information Retrieval**: Automatically fetch documents from the provided URLs, extracting text content from Finance minister budget speeches from 2021 to 2024.

2. **Comparison Analysis**: Analyze the retrieved documents to identify common themes, trends, and differences between different types of speeches and reports. This could involve sentiment analysis, topic modeling, or any other relevant technique to compare the content.

3. **Text Summarization**: Summarize the extracted information into concise, coherent summaries. These summaries should capture the key points and main ideas presented in the documents, enabling users to quickly grasp the essential content without having to read through lengthy texts.

The developed system should be efficient, accurate, and user-friendly, providing valuable insights into the content of Indian government documents for various stakeholders such as researchers, policymakers, and the general public.

## Problem Resolution Approach
***Solution Strategy*** - Build a POC which should solve the following requirements:
- Extract key information, identify trends and comparisons, and generate concise summaries.
- Provide valuable insights for researchers, policymakers, and the public to understand government communication.

***Goal*** - Solving the above two requirements well in the POC would ensure that the accuracy of the overall model is good and therefore further improvisations and customizations make sense.

***Data Used*** -  Indian government budget documents from 2021 to 2024

***Tools used*** - LlamaIndex (only for now) has been used due to its powerful query engine, fast data processing using data loaders and directory readers as well as easier and faster implementation using fewer lines of code.

## System Design
![image](https://github.com/PrabakarTS/SemanticSpotter/blob/main/System-Design.png)


## Lesson Learnt
1.	Efficient Document Retrieval: Leveraged llamaIndex for fast data processing and retrieval from diverse government document sources.
2.	Comparative Analysis Insights: Utilized various indices to analyze and compare Prime Minister speeches, President speeches, committee reports, and budget releases.
3.	Concise Summarization Techniques: Employ HuggingFaceEmbeddings and QdrantVectorStore to summarize key information into coherent summaries.
4.	Effective Tool Selection: Choose appropriate tools like SummaryIndex and VectorStoreIndex for summarization and context retrieval, respectively.
5.	Query Engine Configuration: Configure query engines for summarization and context retrieval, enabling efficient user interaction.
6.	Integration of Multiple Technologies: Integrated llamaIndex, HuggingFaceEmbeddings, and QdrantVectorStore for comprehensive document analysis.
7.	Collaborative Development: Collaborated with diverse tools and libraries to address various aspects of the problem statement effectively.
8.	Scalability Considerations: Consider scalability aspects such as chunk size and context window for efficient processing of large volumes of documents.


