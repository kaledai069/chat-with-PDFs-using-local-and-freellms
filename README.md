## A simple RAG application build for .pdf type with Streamlit which utilizes both local llm and Groq provided (glitched) llm API endpoint. 
### Minimalist UI Interface

<p>PDF file upload interface, which takes some time depending upon system to vectorize documents with OllamaEmbedding and saves the vectors in a FAISS vector store.</p>

<p align='center'>
    <img src="assets/ss_1.png" alt="upload pdf interface" width="600">  
</p>

<p>After vectorizing, user has the option to choose the backend LLM model for chatting with the uploaded pdf file.</p>

<p align='center'>
    <img src="assets/ss_2.png" alt="chatting with pdf interface" width="800">  
</p>
