# Business Process Optimization Bot

This AI based application integrates the Langchain library for conversational AI to create a business process optimization bot. It allows users to upload documents explaining their current business processes. The bot then analyzes these documents and suggests improvements or new processes.


## Installation

Before running the application, ensure you have Python installed on your system. This application has been tested with Python 3.8 and above.

1. **Clone the Repository**:
   ```
   git clone git@github.com:aiproduct-creators/business-ai.git
   cd business-ai
   ```
2. **Set Up a Virtual Environment** (Optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate # On Windows use venv\Scripts\activate
   ```

3. **Install Dependencies**:

   ```
   pip install -r requirements.txt
   ```

4. **Environment Variables**:

   Create a `.env` file in your project root and add your OpenAI API key:

   ```
   OPENAI_API_KEY='your_api_key_here'
   ```
## Running the Application

   To run the application, use the following command:
   ```
   streamlit run app.py
   ```

This command will start the Streamlit server and the application should be accessible in your web browser at `http://localhost:8501`.

## Features

- PDF and Docx File Processing: Read and process content from PDF and Docx files.
- Conversational AI: Interact with a conversational AI model for various tasks.
- Streamlit Interface: A user-friendly interface for interaction and file processing.

