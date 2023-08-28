# Custom Knowledge ChatGPT By Damilola Yinusa - Chat with PDFs

## By Damilola Yinusa

This project demonstrates a custom knowledge chatbot that uses LangChain to handle PDFs, create embeddings, and perform text-based similarity search. The chatbot is designed to interactively answer questions and maintain a chat history. Below are the main sections of the project:

## Table of Contents

1. Installs, Imports and API Keys
2. Loading PDFs and chunking with LangChain
3. Embedding text and storing embeddings
4. Creating a retrieval function
5. Creating a chatbot with chat memory (OPTIONAL)

### Prerequisites

- Python (>=3.6)
- LangChain (>=0.0.150)
- PyPDF2
- pandas
- matplotlib
- textract
- transformers
- openai
- faiss-cpu

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Damilola-Yinusa/chatbot-with-pdfs.git
   cd chatbot-with-pdfs
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Replace `{APIKEYHERE}` in the `OPENAI_API_KEY` environment variable assignment with your actual OpenAI API key.

2. Add your PDF file(s) to the local files in the notebook's folder.

3. Open the Jupyter Notebook where you want to run the chatbot.

4. Run the notebook cell by cell, following the explanations and code provided.

5. Interact with the chatbot using the input prompts. Type 'exit' to stop the chat.

### Explanation

This project demonstrates how to create a custom knowledge chatbot that utilizes LangChain's capabilities for handling PDFs, creating embeddings, and performing text-based similarity search. The main steps include:

1. Installing required packages and setting up API keys.
2. Loading PDFs and chunking text using LangChain to create manageable document units.
3. Embedding text and storing embeddings using LangChain's OpenAIEmbeddings and FAISS vector database.
4. Setting up a retrieval function to find similar documents based on user queries.
5. (Optional) Creating a chatbot with chat memory using a ConversationalRetrievalChain.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, feel free to open an issue or a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
