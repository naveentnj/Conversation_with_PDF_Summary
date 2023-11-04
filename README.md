# Conversation_with_PDF_Summary
Worked with both both Open AI API and HuggingFace API for PDF Text Extraction and summarization in chat format and ask queries related to the PDF

Used Local Cache files for text embedding model from Hugging Face

# Description about the Project
    1. Used Langchain tools to convert PDF text data into vector data and store it in a FAISS database.
    This allows the project to represent PDF text data in a way that can be efficiently processed by LLMs. LLMs can then be used to query and summarize the PDF text data quickly and accurately.

    2. Integrated OpenAI GPT API to query and summarize multiple PDF text documents.
    This allows the project to provide efficient retrieval of relevant information from multiple PDF documents simultaneously. This is useful for tasks such as comparing two or more documents, or finding information that is scattered across multiple documents.

    3. Used Conversation Buffer Memory and Conversational Retrieval Chain to store the queries and answers.
    This allows the project to keep track of the conversation history and use it to inform subsequent responses. This makes the chat app more conversational and engaging, and allows it to provide more relevant and helpful answers to user queries.

    4. Used Hugging Face Transformers to access and fine-tune LLMs.
    Hugging Face Transformers is a popular library for natural language processing (NLP) that provides a unified API for accessing and fine-tuning LLMs. The project uses this library to access the OpenAI GPT API and to fine-tune the model on its own dataset of PDF text data. This allows the project to improve the performance of the model on its specific task.

    5. Used Langchain to integrate the different components of the system.
    Langchain is a library that provides tools for building and deploying large-scale NLP applications. The project uses Langchain to integrate the different components of the system, such as the PDF text extractor, the text-to-embedding converter, the FAISS database, and the OpenAI GPT API. This simplifies the development and deployment of the system.

    6. Provided a chat interface for users to query the summarized PDF text using streamlit.
    - The project creates a Streamlit app that loads the pre-trained LLM and the FAISS database.
    - The app also creates a chat interface using Streamlit widgets.
    - When a user types in a query, the app sends the query to the LLM.
    - The LLM generates a response, which is then displayed to the user in the chat interface.
    - The app also stores the conversation history in memory, so that the LLM can use it to inform subsequent responses.
    - The Streamlit app can be deployed to the cloud using a service such as Heroku, so that it can be accessed by users from anywhere in the world.

    Overall, the project "Chat with PDF using Hugging Face and Open AI" with Conversation Buffer Memory and Conversational Retrieval Chain makes effective use of LLMs to provide a chat interface for users to query and summarize multiple PDF text documents efficiently.

