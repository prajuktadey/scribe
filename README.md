# Scribe: Chat with Your Documents

Scribe is a collaborative project developed by a group of 6 students from Kalinga Institute of Industrial Technology (KIIT) as a minor project for their 6th semester. With Scribe, users can interact with their documents using advanced language models locally, powered by Ollama (mistral model), LangChain, and Chainlit.

## System Requirements

To use Scribe, ensure that you have Python 3.9 or later installed on your system.

## Steps to Replicate 

1. **Clone the Repository:** Begin by cloning the Scribe repository to your local machine.
   ```bash
   git clone https://github.com/prajuktadey/langchain-ollama-chainlit.git
   cd langchain-ollama-chainlit

### Set Up Virtual Environment

Create a virtual environment for the project and activate it.
```bash
python3 -m venv .venv && source .venv/bin/activate
```

### Install Dependencies

Install the required Python packages by running the following command:
```bash
pip install -r requirements.txt
```

### Start the chat UI

Start the chat UI by running the appropriate command based on the example you want to replicate:

```bash
# Chatbot with Document Upload
chainlit run rag.py
```

### Conclusion

Scribe offers a powerful yet simple solution for interacting with your documents using advanced language models. Developed by a team of students from Kalinga Institute of Industrial Technology (KIIT) as a minor project, Scribe leverages the capabilities of Ollama (mistral model), LangChain, and Chainlit to provide an educational tool for exploring the possibilities of natural language processing.

While Scribe is not intended for production use and may require additional configuration depending on your setup, it serves as a testament to the collaborative efforts of its developers and the potential of open-source resources in the field of AI and NLP.

Feel free to explore, modify, and adapt Scribe for your own use cases, keeping in mind that it is designed for educational purposes and should not be deployed in a production environment without proper testing and validation.




