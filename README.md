# PDFChain: Interaction with Documents using LangChain

**Anahita Gupta**  
**Sanchita Ghosh**

PDFChain is a Streamlit-based application that enables conversational question-answering over multiple uploaded PDF documents using a Retrieval-Augmented Generation (RAG) pipeline built with LangChain and FAISS. The system extracts text from PDFs, segments it into overlapping chunks, converts them into vector embeddings, and retrieves semantically relevant context to generate grounded responses via an LLM.

---

## Steps

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Set Up Environment Variables

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_api_key_here
```

### 3. Run the Application

```bash
streamlit run app.py
```

After running the command, the application will open in your browser. Upload your PDF documents and start asking questions.
