# RAG PDF Reader

This repository contains a **RAG (Retrieval-Augmented Generation) PDF Reader** application that leverages AI/ML techniques to read, analyze, and provide relevant information from PDF files. The application uses natural language processing (NLP) to offer a seamless interaction with the content in PDFs by retrieving relevant sections and generating meaningful responses to user queries.

## Features

- **PDF Parsing**: Extracts and processes text from PDF documents.
- **AI-Powered Question Answering**: Uses retrieval-augmented generation (RAG) to provide accurate answers based on PDF content.
- **User-friendly Interface**: Interactive, easy-to-use interface for uploading and interacting with PDFs.
- **Scalable**: Can handle multiple PDFs, making it suitable for research and documentation purposes.

## Technologies Used

- **Python**: Main programming language for the backend.
- **PyTorch**: Used for NLP model integration.
- **LangChain**: Helps in managing complex chains of language models.
- **Streamlit**: Frontend framework used for creating a web-based interface.
- **Numpy, Pandas**: Libraries for data manipulation and processing.
  
## Installation

To run the RAG PDF Reader locally, follow the steps below:

1. Clone this repository:

   ```bash
   git clone https://github.com/Mounishkr/Rag-Pdf-Reader.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Rag-Pdf-Reader
   ```

3. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/MacOS
   env\Scripts\activate     # For Windows
   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Run the application:

   ```bash
   streamlit run app.py
   ```

## Usage

1. Upload a PDF file via the web interface.
2. Enter a query related to the content of the PDF.
3. The application will retrieve relevant sections of the document and generate a detailed response.

## Contributing

Contributions are welcome! If you'd like to improve the project, feel free to fork this repository and submit a pull request with your changes.

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-branch
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m 'Add new feature'
   ```

4. Push to your fork:

   ```bash
   git push origin feature-branch
   ```

5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
