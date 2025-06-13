# Gmail to Discord Forwarding

This project forwards new emails from Gmail to a Discord channel using a bot. It monitors incoming messages and posts summaries to Discord.

## Setup

1. Clone the repository.
2. Create a Google API project and download the OAuth credentials JSON.
3. Set up a Discord bot and get its token and channel ID.
4. Install the dependencies listed in `requirements.txt`.
5. Run the setup script to authorize Gmail access.

```bash
pip install -r requirements.txt
python setup.py
```

## Usage

Start the forwarding service with:

```bash
python gmail2discord.py --token YOUR_DISCORD_TOKEN --channel YOUR_CHANNEL_ID
```

The bot will watch for new messages in your Gmail inbox and forward them to the specified Discord channel.

