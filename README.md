# Retrieval-Augmented Generation Application
### Using LangChain and OpenAI

## Introduction
With this Retrieval-Augmented Generation (RAG) application, you can create chatbots for your documents, books, or files. You can also use it to build rich, interactive AI applications that use your data as a source. 
Examples:
1. Ask questions about a large set of documents
2. Create a customer support chatbot that helps customers by following a set of instructions.
### Creating the RAG application
The process for creating the app is as follows:
1. Split your data into chunks of text (500 to 1000 words) to store your data more efficiently. This allows the retrieval process to capture pieces of information that are more relevant to the query, and the generation by the LLM (OpenAI model) to be more precise. It is also less costly, as only parts of a document will be included in the prompt, instead of the entire document collection.
2.  In language models, this allows the model to understand the meaning and context of words based on their similarity to other words.
3. Use the query input by the user to perform a similarity search and retrieve a set of relevant chunks from the database.
4. The LLM (OpenAI model) uses the relevant chunks as context and sends a response along with its sources.

