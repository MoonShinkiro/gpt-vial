# gpt-vial
A script to access your OpenAI tokens and create a discord chatbot



## Running
1. Acquire and copy your own bot token from https://discord.com/developers/applications/ and check the boxes ```bot``` from OAuth2 section. Make sure to add your bot to your server as well.
2. Open/edit the .env file and paste your bot token to ```TOKEN=``` as well as your ```OPENAI_KEY=```
3. Fill in the discord channel ID in the index.js file where you wish for the bot to speak in 
4. In the folder where /gpt-vial is located, run a terminal line with: ```node index.js load```
