# Enhancing Chatbot's Knowledge Base with Anthropic's Claude and Chroma Database

This project showcases the power of Anthropic's latest language model, Claude, with its large 100k context window and demonstrates how to enhance the chatbot's knowledge base using the Chroma database. The chatbot, equipped with these capabilities, provides detailed information on the latest Dota2 patch notes.

## Prerequisites

Before running the project, ensure that you have the following:

- Python 3.7 or later
- An OpenAI API Key
- An Anthropic API Key

## Installation

To install necessary dependencies, navigate to the project's root directory and run the following commands:

```bash
pip3 install -r requirements.txt
```

This command will install all necessary Python packages listed in the `requirements.txt` file.

## Environment Variables

The project requires the following environment variables:

- `OPENAI_KEY`: Your OpenAI API key.
- `EMBEDDING_MODEL`: The OpenAI model used for text embedding (e.g., `gpt-4`).
- `CLAUDE_KEY`: Your Chroma database credentials.
- `MODEL_NAME`: The Claude model used to generate responses.

Make sure to replace these values with your actual keys and credentials.

## Usage

To start the chatbot, run:

```bash
python3 main.py
```

Once the chatbot is running, you can start the conversation.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

## Contact

For any questions, please contact me on github.