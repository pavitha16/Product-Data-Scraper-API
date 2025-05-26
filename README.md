# Product-Data-Scraper-API

A **FastAPI**-based REST API to extract detailed product information from any e-commerce webpage URL.  
It leverages **Langchain + OpenAI** for intelligent product data extraction and falls back to traditional parsing techniques like JSON-LD and meta tags using **BeautifulSoup** for reliability.



## 🔑 Key Features

- 🧠 **AI-powered Extraction** with Langchain & OpenAI for smart, flexible product data parsing  
- 🔄 **Fallback Parsing** from structured JSON-LD schema and meta tags for robustness  
- 📦 Extracts key product details:
  - Product Name  
  - Product Price  
  - Product URL  
  - Product Image URL  
  - Product Description  
- ⚡ High-performance asynchronous API built with FastAPI  
- 🛠️ Easy to extend and customize for different e-commerce websites  
- 🚀 Ready for deployment with Uvicorn  
-  Website link : https://www.hiketron.com/


## 🛠️ Installation

- Install dependencies:
pip install fastapi uvicorn requests beautifulsoup4 langchain openai

-  Running the API
Start the server with:
uvicorn main:app --host 0.0.0.0 --port 8000
