# Voice Assistant with GPT API and LLM Model

This project aims to create a voice assistant using the GPT API and a large language model (LLM). The voice assistant utilizes natural language processing and generation techniques to understand and respond to user queries in a conversational manner.

## Overview

The voice assistant is built using the GPT (Generative Pre-trained Transformer) API provided by OpenAI. The GPT API allows developers to integrate the power of language models into their applications without the need for extensive training or infrastructure setup.

The large language model (LLM) used in this project is based on the GPT-3.5 architecture. It has been trained on a wide range of text data and can generate coherent and contextually relevant responses based on the given input.

## Functionality

The voice assistant provides the following functionality:

1. **Speech Recognition**: It uses speech recognition technology to convert spoken language into written text. This allows users to interact with the assistant using their voice.

2. **Natural Language Processing**: The assistant applies natural language processing techniques to understand user queries and extract relevant information. It analyzes the input text and identifies the intent and entities present.

3. **Query Processing**: Once the user query is understood, the assistant processes it to generate a meaningful response. It leverages the power of the LLM model to generate human-like and contextually appropriate replies.

4. **Text-to-Speech Conversion**: The generated response is converted back into speech using text-to-speech synthesis. This enables the assistant to communicate with the user in a natural and intuitive manner.
# Getting started.

## Prerequisites

Before starting with this project, make sure you have the following:

1. OpenAI GPT API access: You should have an API key or credentials to access the GPT API. If you don't have one, you can sign up for the OpenAI GPT API and obtain the necessary credentials.

2. Python environment: Ensure that you have Python installed on your machine. The code provided in this project is compatible with Python 3.

## Installation

Follow the steps below to set up the project:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/isakovsh/voice_chat_bot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd voice_chat_bot
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Set up the GPT API:

   - Open the `config.py` file in a text editor.
   - Replace `<YOUR_API_KEY>` with your actual GPT API key.
   - Save and close the file.

## Usage

To run the voice assistant, execute the following command:

```bash
streamlit run demo.py

```

The voice assistant will start listening for voice commands. You can speak naturally and ask questions or give instructions. The assistant will process your command using the GPT API and provide a spoken response.


## Troubleshooting

If you encounter any issues while setting up or running the voice assistant, consider the following:

- Double-check that you have entered the correct GPT API credentials in the `config.py` file.
- Ensure your Python environment meets the project's requirements specified in the `requirements.txt` file.
- Check the OpenAI GPT API documentation for any updates or changes that may affect the integration.

If the problem persists, you can refer to the project's issue tracker on GitHub or seek help from the OpenAI community.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to modify and distribute it as per the terms of the license.

## Acknowledgements

This project is built upon the OpenAI GPT API and the LLM model developed by OpenAI. We would like to express our gratitude to OpenAI and the community for their contributions to natural language processing and voice assistants.


## Conclusion

By combining the power of the GPT API and a large language model, this voice assistant project enables natural and interactive communication between users and the assistant. With further enhancements and refinements, it has the potential to be integrated into various applications and platforms, providing users with a seamless and intuitive voice-driven experience.

Remember to refer to the official documentation for the GPT API and any other libraries or services used in the project for detailed instructions and guidelines. Happy coding!
