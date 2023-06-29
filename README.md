# paradox-gpt-discord-bot
This JavaScript script creates a bot for Discord using the discord.js library and integrates it with OpenAI's GPT-4 model using OpenAI's Node.js library. The bot listens to incoming messages in a specific Discord channel, carries a conversation with users using OpenAI's model, and responds back in the same channel.

#Prerequisites 

1. **Node.js**: This project is based on Node.js. Make sure to install Node.js and npm.
2. **Discord Developer Account**: You will need a Discord developer account to create and manage bots.
3. **OpenAI API Key**: You need an API key from OpenAI to use the GPT-4 model.
4. **Required Dependencies**: The required dependencies are `discord.js`, `dotenv`, and `openai`.
5. The bot uses environment variables stored in the `.env` file for configuration. These are:

- `TOKEN`: The Discord bot token. This is unique to each bot, and is used to log the bot into Discord.
- `API_KEY`: The OpenAI API key. This is used to authenticate requests to the OpenAI API.
- `CHANNEL_ID`: The ID of the channel in which the bot will listen for and send messages.
