# AI-Powered Knowledge Retrieval System using RAG

•	Designed & developed a Retrieval Augmented Generation (RAG) system that combines traditional search capabilities with generative AI to answer user queries based on the knowledge base for accurate and context aware answers.
•	Worked on pinecone to create the database, Dense embeddings for similarity matrix, Hugging Face Model LLM for content generation & created a Rest API of the function with the outcome of reducing LLM hallucination by 50%.

# Project Setup Instructions

## Prerequisites
Before setting up the project, ensure you have the following installed:
- Python 3.7 or later
- pip (Python package manager)

---

## Step 1: Install Required Python Packages
Run the following commands in your terminal to install the necessary dependencies:

```bash
!pip3 install -qU \
    langchain \
    tiktoken \
    datasets \
    pinecone-client

!pip3 install protobuf==3.20.3
!pip3 install apache-beam==2.50.0
!pip install fastapi uvicorn
```

---

## Step 2: Configure API Keys
### 1. Pinecone API Key
Generate a **PINECONE_API_KEY** from your Pinecone project dashboard:
1. Go to [Pinecone Dashboard](https://www.pinecone.io/).
2. Create or access your project.
3. Copy the API Key provided for your project.

Set the key in your environment:
```bash
export PINECONE_API_KEY="your_pinecone_api_key"
```

### 2. Ngrok Authentication Token
Generate an **NGROK_AUTH** token to establish a connection with Ngrok:
1. Sign up or log in to [Ngrok](https://dashboard.ngrok.com/).
2. Navigate to **Authentication** in your dashboard.
3. Copy your authentication token.

Set the token in your environment:
```bash
export NGROK_AUTH="your_ngrok_auth_token"
```

------------------------------------------------------------------------------

# sample querie and output

![image](https://github.com/user-attachments/assets/e8946765-72f2-429d-9398-fb2fdf9fd602)

![image](https://github.com/user-attachments/assets/58dea171-59be-4e7b-b466-583734491b26)

