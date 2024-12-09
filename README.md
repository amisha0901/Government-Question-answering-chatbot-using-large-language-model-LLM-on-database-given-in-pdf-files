# Government-Question-answering-chatbot-using-large-language-model-LLM-on-database-given-in-pdf-files

1)	Employed PyPDF2 to extract text from uploaded PDF
2) 	Employed LangChain and OpenAI for natural language processing 3(NLP)
3)  Implemented a question-answering system with LangChain
4) 	Integrated FAISS for efficient document storage and retrieval.
5) 	Utilized Python for the backend development, incorporating Flask for the web interface

Features:-

1)PDF Text Extraction: Utilizes PyPDF2 to extract text from uploaded PDF files containing government scheme information.

2)Question-Answering System: Powered by LangChain and OpenAI, the system processes user queries and provides contextually relevant answers based on the extracted information from PDFs.

3)Efficient Document Storage and Retrieval: Integrates FAISS for efficient storage, indexing, and retrieval of documents, enabling quick access to relevant sections of the PDFs.

4)Natural Language Processing (NLP): Uses advanced NLP techniques to understand user queries and retrieve the most accurate answers from the documents.

5)Web Interface: The system is deployed with a Flask-based web interface, allowing users to interact with the chatbot, ask questions, and receive answers in real time.


Technologies Used:-

1.PyPDF2: For extracting text data from PDF files.

2.LangChain: For processing natural language queries and building the question-answering logic.

3.OpenAI: Used for leveraging large language models (LLMs) to understand and generate answers.

4.FAISS: For efficient document storage, indexing, and semantic search.

5.Flask: For building the web interface and connecting the backend to the user-facing application.
6.Python: Main programming language used for backend development and integration.

How to Run:-

1.Install the required dependencies: pip install -r requirements.txt.

2.Run the Flask app: python app.py.

3.Upload the PDF containing government schemes, input a question, and interact with the chatbot for real-time answers.

Future Improvements:-

1.Support for Multi-file Upload: Enabling users to upload multiple PDFs at once to cover a wider range of government schemes.

2.Enhanced Query Understanding: Implementing more advanced NLP techniques for better understanding of complex user queries.

3.User Feedback: Incorporating user feedback to refine the accuracy of answers over time.

4.Multilingual Support: Adding support for government schemes in different languages to cater to a larger audience.
