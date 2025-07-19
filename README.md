# RAG Implementation from Scratch 🧠🔍
This repository demonstrates a **from-scratch implementation** of a simple **Retrieval-Augmented Generation (RAG)**
system using basic Python and NLP concepts — without using high-level libraries like `TF-IDFVectorizer`.

## 📌 What is RAG?
**Retrieval-Augmented Generation (RAG)** combines:
- 🔍 **Retrieval**: fetching relevant documents or passages from a knowledge base.
- 🧠 **Generation**: using a language model to generate answers based on those documents.
This makes it possible to answer user queries with external knowledge, without needing to retrain the model.

What’s Inside?
`RAG_implemention_from_scratch.ipynb`
This Jupyter notebook covers:
- 📚 Document corpus creation  
- 🧹 Preprocessing (tokenization, cleaning)  
- 🧾 Manual vector creation (word frequency)  
- 🧮 Cosine similarity for retrieval  
- 🧠 Simple QA logic based on top document  

## 🛠️ How It Works

1. **Corpus** – A set of static sentences used as a knowledge base.  
2. **Query Input** – User provides a question.  
3. **Preprocessing** – Clean and tokenize documents and queries.  
4. **Manual Vectorization** – Count word occurrences in both corpus and query.  
5. **Cosine Similarity** – Compute similarity between query and all documents.  
6. **Answer Generation** – Select the most relevant document and generate a response.  


