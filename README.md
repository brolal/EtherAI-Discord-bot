# EtherAI Discord Bot

## Description
EtherAI is an advanced Discord bot specifically designed for the Ethereum Classic community. As an interactive AI assistant, it leverages the power of OpenAI's GPT-4 to provide real-time responses to various queries related to Ethereum technology, Solidity programming, and blockchain concepts. The bot is tailored to Discord's community, focusing on technical accuracy, readability, and adherence to Discord's message size limitations.

## Features
- **Intelligent Query Handling**: Responds to user queries about Ethereum Classic and related technologies, utilizing enhanced regular expressions for accurate identification.
- **Code Example Integration**: Provides Solidity 0.8.x code examples, formatted within Discord's Markdown environment.
- **Discord-Friendly Formatting**: Structures responses to fit within Discord's 2000 character limit per message, ensuring clarity and conciseness.
- **Engaging and Educational**: Designed to enhance user experience on Discord with informative replies, making learning about Ethereum Classic both engaging and accessible.

## Setup
1. **Environment Setup**:
   - Install Python 3.8 or higher.
   - Install required Python packages: `discord.py`, `httpx`, and `python-dotenv`.

2. **Discord and OpenAI API Tokens**:
   - Obtain a Discord Bot Token from the [Discord Developer Portal](https://discord.com/developers/applications).
   - Obtain an OpenAI API key from [OpenAI](https://openai.com/).

3. **Environment Variables**:
   - Create a `.env` file in your project directory.
   - Add the following lines to the `.env` file:
     ```
     DISCORD_TOKEN=your_discord_bot_token
     OPENAI_API_KEY=your_openai_api_key
     ```

4. **Running the Bot**:
   - Execute the bot script: `python bot_script.py`.

## Usage
- Invite the bot to your Discord server.
- The bot listens to messages and responds to queries related to Ethereum Classic and Solidity.
- For best results, keep queries clear and concise.

## Contributions
- Contributions to EtherAI are welcome. Please feel free to fork the repository, make changes, and submit pull requests.

## License
- EtherAI is released under [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments
- This bot utilizes OpenAI's GPT model for generating responses.
- Thanks to the Ethereum Classic community for inspiration.
---
