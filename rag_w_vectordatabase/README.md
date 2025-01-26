## RAG Application with Chroma Vector Database

In this application, Llama 3.2 with 1 billion parametes is utilized. It is provided with context of personal information of an individual
(my cover letter and resume in this case) so that it can answer questions regarding that person.

To load the data Docling is used which is an open source framework designed to make document processing easier for generative AI applications.

Chroma is used to handle creating a vector database with embeddings generated using sentence transformers from Hugging Face. 
