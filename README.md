# 🎓 College Admission Agent (RAG-Based)

This project is a smart AI-powered assistant that helps prospective students with college admission queries using **Retrieval-Augmented Generation (RAG)**. Built on **IBM Watsonx.ai** and powered by **LLaMA-3** or **Granite** large language models, it provides instant, accurate, and document-grounded answers about courses, eligibility, fees, scholarships, and deadlines.

---

## 🚀 Features

- ✅ Natural language interface for admission Q&A  
- ✅ Retrieval-Augmented Generation (RAG) using embedded documents  
- ✅ Uses IBM Watsonx.ai with LLaMA-3 or Granite models  
- ✅ Optionally supports document upload (prospectus, FAQs, etc.)  
- ✅ Simple UI using Watsonx Agent Lab  
- ✅ Works even without document upload for general responses

---

## 🧱 Architecture

1. **User Input**: Student asks a question in plain language  
2. **Retriever**: (Optional) Fetches relevant chunks from stored admission documents  
3. **LLM (Watsonx)**: Processes question + context and generates an accurate answer  
4. **Response**: AI returns a grounded, informative answer in real time

---

## 🧠 Technologies Used

- **IBM Watsonx.ai**
- **LLaMA-3-70B-Instruct** or **Granite-13B-Instruct**
- **IBM Cloud Object Storage**
- **Watsonx Agent Lab** (LangGraph + ReAct)
- *(Optional)* FAISS + LangChain (Python RAG pipeline)

---

## 📦 Folder Structure (if using code)

