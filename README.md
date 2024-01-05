# Blaq's Medical Chatbot
### Powered by 🅱🅻🅰🆀

Blaq's Medical Chatbot is an innovative tool designed to provide quick and reliable medical information. Utilizing state-of-the-art language models and vector stores, this bot answers user queries with precision. This README guides you through setup and usage.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Blaq's Medical Chatbot leverages advanced technology to deliver medical insights efficiently. It's built using a quantized language model, making it compatible with CPU environments, thus broadening its accessibility.

## Prerequisites

Before starting, ensure you have:

- Python 3.6 or higher
- Required Python packages (install via pip):
    - langchain
    - chainlit
    - sentence-transformers
    - faiss
    - PyPDF (for PDF document loading)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Blaqadonis/medical-chatbot.git
   cd langchain-medical-bot

    ```

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the quantized language model for CPU compatibility: [huggingface model](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa0pFYmtnQXQ0U2RSMlUwX1NXWnBablJneFJpUXxBQ3Jtc0trbC01VlZ5RmFhYXhZWV8yQmJ4RWxHNFBfWUdfWHBlalN0SGVUakdUbnE4MmNWclUtMFFNa1JLZTNUSzJuZ2hCc0hUTjdNa3hsQzFJU3ZoMWN4eGdKODVVVzc3RzV4MmxYalFvUUJWUGZBYi1Obmhldw&q=https%3A%2F%2Fhuggingface.co%2FTheBloke%2FLlama-2-7B-Chat-GGML%2Fblob%2Fmain%2Fllama-2-7b-chat.ggmlv3.q8_0.bin&v=kXuHxI5ZcG0)

5. Set up the necessary paths and configurations in your project, including the `DB_FAISS_PATH` variable and other configurations as per your needs.

## Getting Started

To get started with this Bot, you need to:

1. Set up your environment and install the required packages as described in the Installation section.

2. Configure your project by updating the `DB_FAISS_PATH` variable and any other custom configurations in the code.

3. Prepare the language model and data as per the Langchain documentation.

4. Start the bot by running the provided Python script or integrating it into your application.

## Usage

Blaq's Medical Chatbot can be used for answering medical-related queries. To use the bot, you can follow these steps:

1. Start the bot by running your application or using the provided Python script.

2. Send a medical-related query to the bot.

3. The bot will provide a response based on the information available in its database.

4. If sources are found, they will be provided alongside the answer.

5. The bot can be customized to return specific information based on the query and context provided.

## Screenshots

- **UI:**
![image](https://github.com/Blaqadonis/medical-chatbot/assets/100685852/0c7e71ad-870d-4266-b9ed-0f8232da19f0)



## Contributing

Contributions to Blaq's Medical Chatbot are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository to your own GitHub account.

2. Create a new branch for your feature or bug fix.

3. Make your changes and ensure that the code passes all tests.

4. Create a pull request to the main repository, explaining your changes and improvements.

5. Your pull request will be reviewed, and if approved, it will be merged into the main codebase.

## License

This project is licensed under the MIT License.

---

For more information on how to use, configure, and extend the Llama2 Medical Bot, please refer to the Langchain documentation or contact the project maintainers.
