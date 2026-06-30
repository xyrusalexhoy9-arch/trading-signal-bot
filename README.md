# 1. Create folder
mkdir trading-signal-bot
cd trading-signal-bot

# 2. Setup
python -m venv venv
source venv/bin/activate  # Mac/Linux
# or on Windows: venv\Scripts\activate

# 3. Install
pip install discord.py python-dotenv

# 4. Create .env file with your bot token
echo "DISCORD_TOKEN=your_token_here" > .env

# 5. Create bot.py (see code below)

# 6. Run
python bot.py
