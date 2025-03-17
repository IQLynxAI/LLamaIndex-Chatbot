# **LLamaIndex Chatbot**

Welcome to the **LLamaIndex Chatbot** repository! This project leverages **Hugging Face models** and **OpenAI's APIs** to fine-tune large language models for chatbot interactions and text generation. It also integrates **LLamaIndex** for efficient retrieval and response generation.

## **Project Overview**

This chatbot is designed to:
- Fine-tune language models for domain-specific conversations.
- Generate intelligent responses using **Hugging Face models** and **OpenAI**.
- Store and retrieve knowledge using **LLamaIndex** and **OpenSearch**.
- Perform advanced data preprocessing for improved model performance.

## **Project Structure**

```
LLamaIndex-Chatbot/
│── App/
│
│── src/
│   ├── Chatbot/
│   │   ├── QueryEngine.py  # Handles query processing
│   │   ├── prompt.py  # Custom prompt generation
│   │
│   ├── Finetuning/
│   │   ├── Data_Preprocessing/
│   │   │   ├── Preprocessing.py  # Data cleaning and preparation
│   │
│   ├── Store_in_OpenSearch/
│   │   ├── vector_store.py  # Storing embeddings in OpenSearch
│   │   ├── RetrieveVectorStoreIndex.py  # Retrieving stored vectors
│
│── Documents/
│   ├── Sample documents for chatbot context
│
│── Notebooks/
│   ├── Finetuning_Model_with_LlamaIndex.ipynb  # Fine-tuning notebook
│   ├── OpenSearchVectorStore.ipynb  # Using OpenSearch for retrieval
│
│── main.py  # Main script to run the chatbot
│── test.py  # Test script for debugging
│── requirements.txt  # Required dependencies
│── README.md
```

## **Installation & Setup**

To get started, clone the repository:

```bash
git clone https://github.com/IQLynxAI/LLamaIndex-Chatbot.git
cd LLamaIndex-Chatbot
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## **Usage**

### **Run the Chatbot**

To start the chatbot:
```bash
python main.py
```

### **Fine-tuning the Model**

Use the Jupyter notebook to fine-tune the model:
```bash
jupyter notebook Notebooks/Finetuning_Model_with_LlamaIndex.ipynb
```

### **OpenSearch Vector Store**

To store and retrieve indexed knowledge:
```bash
python src/Store_in_OpenSearch/vector_store.py
python src/Store_in_OpenSearch/RetrieveVectorStoreIndex.py
```

## **Contributing**

We welcome contributions! If you would like to contribute, please fork this repository and submit a pull request with detailed changes.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Contact**

For questions or feedback, feel free to reach out:

- **Name**: IQLynxAI
- **Email**: [contact@iqlynxai.com](mailto:contact@iqlynxai.com)
- **GitHub**: [IQLynxAI](https://github.com/IQLynxAI)
- **LinkedIn**: [IQLynxAI](https://www.linkedin.com/company/iqlynxai/)
- **Instagram**: [IQLynxAI](https://www.instagram.com/iqlynx.ai/)
