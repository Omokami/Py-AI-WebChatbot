# AI-Powered Website Chatbot

Welcome to the Website-to-Chatbot project! This application allows you to create a chatbot that can answer questions based on the content of any website. It leverages the power of OpenAI's language models to provide accurate and relevant responses, making it an excellent tool for improving user engagement on your website.

## Video Preview
[![Video Preview](https://github.com/zima-0201/Project-Images/blob/main/video%20preview/Py-AI-WebChatbot.jpeg)](https://autobuffy-ebay.s3.eu-north-1.amazonaws.com/Detroit+Axle/Py-AI-WebChatbot.mp4)

## Features

- **ChatGPT Integration:** Instantly answer your visitors' questions with a personalized chatbot trained on your website content.
- **Document Ingestion:** Easily ingest content from any URL to train the chatbot.
- **Interactive Chat:** Users can interact with the chatbot through a simple and intuitive chat interface.
- **Streamlit Support:** The application includes a Streamlit interface for easy deployment and testing.
- **Modular Code:** The project is designed with modularity in mind, making it easy to extend and customize.

## Getting Started

Follow these steps to set up and run the Website-to-Chatbot application:

### Prerequisites

- Python 3.8 or higher
- OpenAI API Key

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Anil-matcha/Website-to-Chatbot.git
   cd Website-to-Chatbot
   ```

2. **Create a Virtual Environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set OpenAI API Key:**

   ```bash
   export OPENAI_API_KEY=your_openai_api_key   # On Windows, use `set OPENAI_API_KEY=your_openai_api_key`
   ```

### Running the Application

#### Command Line Interface

1. **Run the Main Script:**

   ```bash
   python main.py
   ```

2. **Modify URL and Query:**
   
   Change the `url` and `query` variables in the `main.py` script to test with different content.

#### Streamlit Interface

1. **Run the Streamlit App:**

   ```bash
   streamlit run streamlitui.py
   ```

2. **Interact with the Chatbot:**
   
   Open the provided Streamlit URL in your browser and interact with the chatbot.

## Usage

### Ingesting a URL

To ingest a URL and train the chatbot:

1. Enter the URL in the input field.
2. The system will fetch and process the content, splitting it into manageable chunks.
3. The content is stored in a vector database for efficient retrieval during querying.

### Asking Questions

1. Enter your question in the chat input field.
2. The chatbot processes the question and retrieves relevant information from the ingested content.
3. The chatbot responds with an accurate and relevant answer.

## Example Projects

Explore similar projects for inspiration:

- [Chat with PDF](https://github.com/Anil-matcha/ChatPDF)
- [Chat with CSV](https://github.com/Anil-matcha/Chat-With-Excel)
- [Chat with YouTube](https://github.com/Anil-matcha/Chat-Youtube)
- [ChatGPT in Discord](https://github.com/Anil-matcha/DiscordGPT)

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.
