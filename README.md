
# AICTE Internship Chatbot

This project is an implementation of a chatbot using Natural Language Processing (NLP) techniques. The chatbot is designed to understand and respond to user input based on predefined intents. The project includes a user-friendly interface created with Streamlit.

---

## Features
- Intent classification using TF-IDF vectorization and Logistic Regression.
- Interactive web-based interface using Streamlit.
- Real-time chatbot responses.
- Chat history stored in CSV format.

---

## Prerequisites

Before running this project, make sure you have the following installed on your system:

- Python 3.8 or higher
- Git
- A code editor like Visual Studio Code or PyCharm

---

## Setup and Installation

Follow these steps to set up and run the project:

1. **Clone the Repository**  
   Clone this repository to your local system using the following command:
   ```bash
   git clone https://github.com/Novius-Ajeet/AICTE_internship_chatbot.git
   ```

2. **Navigate to the Project Directory**  
   Change the current directory to the project folder:
   ```bash
   cd AICTE_internship_chatbot
   ```

3. **Create a Virtual Environment** (Optional but recommended)  
   Create a virtual environment to isolate the project dependencies:
   ```bash
   python -m venv chatbot_env
   source chatbot_env/bin/activate      # For Linux/Mac
   chatbot_env\Scripts\activate         # For Windows
   ```

4. **Install Dependencies**  
   Install the required Python libraries by running:
   ```bash
   pip install -r requirements.txt
   ```

5. **Download NLTK Data**  
   Ensure the necessary NLTK data is downloaded:
   ```python
   python
   >>> import nltk
   >>> nltk.download('punkt')
   >>> exit()
   ```

6. **Prepare the Intents File**  
   Ensure the `intents.json` file is located in the project directory. This file contains the intents, patterns, and responses for the chatbot.

---

## Running the Chatbot

1. **Run the Streamlit Application**  
   Launch the chatbot interface using Streamlit:
   ```bash
   streamlit run chatbot.py
   ```

2. **Interact with the Chatbot**  
   Open the Streamlit app in your default browser. You can now interact with the chatbot.

---

## Project Structure

- `chatbot.py`: Main application file for running the chatbot.
- `intents.json`: JSON file containing intents, patterns, and responses.
- `requirements.txt`: File listing all Python dependencies.
- `chat_log.csv`: File where conversation history is stored (generated after running the chatbot).

---

## Future Enhancements

- Add contextual understanding using advanced NLP models like transformers.
- Expand the intents dataset for better coverage.
- Deploy the chatbot on a cloud platform like AWS or Azure.

---

