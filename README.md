# Private_Llama_bot

Creating a domain specific ai chat bot for private use. Currently it reads the data from a pdf obtianed online of a user guide to a samsung phone. The words from the pdf are quantized and embedded. The embeddings are stored in an FAISS vector store. This is then used to find user guide specific questions that are asked to the llm. Currently only back-end. 

Models folder should contain the llama-2 bin file, which can be downloaded from the models section in hugging face.
