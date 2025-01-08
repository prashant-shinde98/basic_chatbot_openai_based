# Basic Chatbot using OpenAI GPT-4 Mini

This repository contains a basic chatbot implementation using OpenAI's GPT-4 Mini model. The chatbot is designed to handle user queries interactively and showcase the capabilities of the OpenAI API in building conversational AI applications.

## Features

- **Interactive Chat:** Engage in a conversational interface with the chatbot.
- **OpenAI API Integration:** Utilizes OpenAI's GPT-4 Mini model for natural language understanding and response generation.
- **Simple Setup:** Easy to configure and extend for various use cases.

## Repository Link

[Basic Chatbot Repository](https://github.com/prashant-shinde98/basic_chatbot_openai_based)

## Prerequisites

Before running the chatbot, ensure you have the following:

- Python 3.7 or higher
- OpenAI API key

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/prashant-shinde98/basic_chatbot_openai_based.git
   cd basic_chatbot_openai_based
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key as an environment variable:

   ```bash
   export OPENAI_API_KEY='your_api_key_here'
   ```

   Replace `your_api_key_here` with your actual OpenAI API key.

## Usage

Run the chatbot script:

```bash
python chatbot_OpenAI.py
```

The chatbot will start, and you can begin interacting with it by typing your messages.

## File Structure

- `chatbot_OpenAI.py`: Main script for running the chatbot.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project documentation.

## How to Extend

To customize the chatbot or enhance its functionality:

1. **Modify the prompt:** Adjust the initial system message in the code to change the chatbot's behavior.
2. **Add custom logic:** Implement additional functionality like storing chat history, integrating with external APIs, or deploying the chatbot on a web or mobile platform.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenAI](https://openai.com) for providing the GPT-4 Mini API.
- Inspiration from various open-source chatbot projects.
