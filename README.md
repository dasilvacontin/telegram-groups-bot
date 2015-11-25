# Telegram Groups Bot

This bot can be used to manage multiple Telegram topic group chats.


## API

The bot provides the following commands:

- `/help` Show help
- `/groups` Show list of available groups
- `/join <topic>` Show the invite link for that group


## Development

Export env variables that control the logging and specify the bot token:

    export RUST_LOG=telegram_groups_bot=debug
    export TELEGRAM_BOT_TOKEN=<your-token>

Then run the code:

    cargo run


## License

MIT License
