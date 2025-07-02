# NCV
Modular pipeline to ingest PDFs into portable vector stores with metadata. Separates ingestion from retrieval, enabling reuse of knowledge bases across machines without reprocessing. Supports semantic search and metadata filtering for document intelligence tasks.
---  ## 📚 PDF-to-Vector Knowledge Base Pipeline  
This repository contains a modular pipeline for ingesting PDF documents into vector stores and retrieving semantically relevant content using metadata filtering. Designed for scalability and reusability, this system separates the **document ingestion** process from the **retrieval and filtering logic**, enabling seamless portability of knowledge bases across machines or environments.  #
## 🔧 Features  
* **Data Ingestion**   Extracts and processes text from PDF files (including OCR if needed) and converts them into vector embeddings using sentence transformers.
* * **Portable Vector Stores (Knowledge Bases)**   Embeddings are stored in categorized vector databases (e.g., by domain or use case), which can be transferred and reused across machines without re-running ingestion scripts.  
* **Metadata-Driven Retrieval**   Enables retrieval of relevant content chunks using both semantic similarity and fine-grained metadata filters (e.g., document type, company name, year).
* * **Separation of Concerns**   Clean separation between:    * Ingestion logic (run once to create the store)   * Retrieval logic (used repeatedly in different contexts)  
### 🎯 Use Case  Perfect for building reusable, portable, and scalable **document intelligence systems**, especially for tasks like ESG reporting, enterprise search, and RAG (retrieval-augmented generation) pipelines.  ---  Let me know if you want this adapted for a `README.md` layout or if you'd like badges, usage examples, or diagrams included.
