# Scalar_Field
# Scalar QA Agent

A Question Answering (QA) agent designed to extract insights from SEC filings and financial documents using modern NLP techniques, vector databases, and large language models.

## 🧠 Features

- Retrieves and processes SEC filings using `sec-api` and `edgartools`
- Generates embeddings using `FAISS` for fast semantic search
- Integrates with OpenAI and `LangChain` for question answering
- Easily extendable and notebook-driven development

## 🚀 Installation

To get started, install the required Python packages:

```bash
pip install sec-api edgartools transformers faiss-cpu langchain openai
⚙️ Setup
Make sure to set your OpenAI API key:

python
Copy
Edit
import os
os.environ["OPENAI_API_KEY"] = "your-api-key"
You may also need an API key for sec-api depending on usage.

📈 Usage
Clone or download the repository.

Open the Scalar_QA_Agent.ipynb notebook.

Run each cell sequentially to:

Install dependencies

Retrieve and parse SEC filings

Generate and store embeddings

Query the data using natural language

💡 Example Query
“What are the main business risks mentioned in the latest 10-K filing?”

The agent will retrieve the most relevant excerpts and generate a concise, LLM-powered answer.

📁 File Structure
Scalar_QA_Agent.ipynb – Main notebook containing the full QA pipeline.

README.md – Project overview and usage instructions.

📌 Dependencies
sec-api

edgartools

transformers

faiss-cpu

langchain

openai
