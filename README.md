# Question and Answering Application

This is a question-and-answering application. The user provides a link to a webpage on which they want to ask questions. After processing the link, the application automatically creates a 100 words summary, a Twitter tweet, and a LinkedIn post as per the content in the link. After this, users can ask their questions which are answered only from the information available in the webpage link provided.

This application uses:
- Google's Vertex AI PaLM API for text embedding and text answering
- Langchain framework for creating the embedding index and document retrieval
- StreamLit Framework for Application Development

