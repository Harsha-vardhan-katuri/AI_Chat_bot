# Healthcare Assistant Chatbot

## Overview
The Healthcare Assistant Chatbot is an AI-powered chatbot designed to assist users with healthcare-related queries. It provides basic responses to symptoms, appointment scheduling, and medication-related questions. For other queries, it generates responses using the `DistilGPT-2` model.

## Technologies Used
- **Programming Language:** Python 3.10
- **Framework:** Streamlit
- **Natural Language Processing (NLP):** NLTK (Natural Language Toolkit)
- **Machine Learning Model:** Hugging Face Transformers (`DistilGPT-2`)

## Tools Used
- **IDE:** Visual Studio Code (VS Code)
- **Libraries:**
  - `streamlit` for the user interface
  - `nltk` for text processing (tokenization and stopword removal)
  - `transformers` for text generation

## Installation and Setup
### Prerequisites
- Python 3.10 must be installed on your system.
- Install the required dependencies using the following command:
  ```sh
  pip install -r requirements.txt
  ```
- Download required NLTK resources:
  ```python
  import nltk
  nltk.download('punkt')
  nltk.download('stopwords')
  ```

## How to Clone and Run the Chatbot
1. Open a terminal or command prompt.
2. Clone the GitHub repository:
   ```sh
   git clone https://github.com/yourusername/healthcare-chatbot.git
   ```
3. Navigate to the project directory:
   ```sh
   cd healthcare-chatbot
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
5. Run the following command to start the Streamlit application:
   ```sh
   streamlit run chatbot.py
   ```
6. The chatbot UI will open in a web browser where you can interact with it.

## Features
- Provides predefined responses for common healthcare-related queries.
- Uses `DistilGPT-2` for generating responses to other questions.
- Simple and interactive UI using Streamlit.

## Notes
- The chatbot provides general information and should not be used as a substitute for professional medical advice.
- For critical health concerns, always consult a qualified healthcare provider.

## Future Enhancements
- Integration with a medical knowledge base for more accurate responses.
- Voice input support.
- Enhanced response filtering for better user experience.

