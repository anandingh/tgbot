# tgbotGet Telegram Bot Token
Open Telegram and search for @BotFather
Create new bot with /newbot
Copy the provided HTTP API token
Get Hyperbolic API Key
Sign Up or Log In at Hyperbolic Website
Go to Settings → API Keys
Create/copy your API key
🛠️ Environment Set Up
Create .env file using the below command
nano .env
Now input your Telegram Bot Token
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
Now save this file using Ctrl + X and then Y and then press Enter
⚡ Run the bot
Create a screen session
screen -S hyperbolic
Now run the below command
node bot.js
Now detach from this screen session using Ctrl + A, then press D
📜 Commands
Command	Description
/start	Start the bot
/switch	Change model
/remove	Remove API key
/bulk
/help	Show commands
🔒 Security
API keys stored only in session memory
Keys automatically cleared with /remove command
No persistent storage of credentials
