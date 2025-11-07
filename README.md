This project is a multimodal chatbot built for the insurance industry, leveraging a Retrieval-Augmented Generation (RAG) pipeline with LangChain. It uses ChromaDB as a vector store and all-MiniLM-L6-v2 for generating text embeddings, ensuring that responses are grounded in a private knowledge base.

The interactive UI is built with Gradio and integrates several models to handle multimodal queries:

Text Generation: Ollama (Mistral-7b)

Image Generation: DALL·E

Text-to-Speech: GPT-4-tts

Prompt engineering techniques were applied to fine-tune model behavior, significantly reducing hallucinations and improving the accuracy of the chatbot's responses.
