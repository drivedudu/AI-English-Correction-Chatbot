# AI-Powered English Correction Chatbot

This project demonstrates how to create an AI-powered chatbot using OpenAI's GPT-3.5 model to convert non-standard English statements into standard English. The chatbot is implemented using the Gradio interface for easy interaction.

## Objective

The main objective of this project is to use AI to correct non-standard English sentences, providing users with grammatically accurate responses.

## Features

- **AI Model**: Utilizes OpenAI's GPT-3.5-turbo model.
- **User Interaction**: Gradio interface for easy input and interaction.
- **Dynamic Response**: Generates and updates responses based on user input.

## Key Learnings

- **AI Language Models**: How to use GPT-3.5 for language correction tasks.
- **Model Configuration**: Setting up and tuning model parameters for desired outcomes.
- **User Interface**: Creating a simple and effective UI with Gradio.

## Setup

### Prerequisites

- Python 3.7 or higher
- Gradio
- OpenAI Python client

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/drivedudu/AI-English-Correction-Chatbot.git
    cd AI-English-Correction-Chatbot
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Set up your OpenAI API key:
    - Create a file named `gpt.txt` and place your OpenAI API key in it.

## Usage

1. Open the provided local or public URL to interact with the chatbot.

## Code Explanation

The main script sets up the Gradio interface and configures the GPT-3.5 model.

### Key Functions

- **gpt_response**: Handles user input, generates a response from the model, and updates the conversation history.
- **gpt_response_ui**: Integrates the `gpt_response` function with the Gradio UI, providing real-time responses.


## Conclusion

This project demonstrates the power of AI in language correction tasks, highlighting the importance of clear input structuring and parameter tuning to achieve effective results. The Gradio interface makes interaction simple and user-friendly.

---

Feel free to customize this README to better fit your project and audience.
