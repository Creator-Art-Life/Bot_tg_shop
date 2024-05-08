# Shop Telegram Bot with Admin Panel

This project is a Telegram bot designed for managing a shop with an accompanying admin panel. The bot is built using the aiogram 3 framework.

## Features

- **Shop Functions:** Users can browse products, add them to their cart, and place orders.
- **Admin Panel:** Allows administrators to manage products, orders, and users.
- **Access Control:** Admin panel access is granted by promoting the bot to an administrator in a Telegram chat and issuing the /admin command.

## Requirements

- Python 3.7+
- aiogram 3
- Other dependencies as listed in `requirements.txt`

## Installation

1. Clone the repository:

```
git clone https://github.com/Creator-Art-Life/Bot_tg_shop.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Set up your Telegram bot:

   - Create a new bot using BotFather on Telegram.
   - Obtain your bot's API token.

4. Configuration:

   - Create a `.env` file in the root directory.
   - Add your bot's API token to the `.env` file:

   ```
   TOKEN=your_bot_api_token_here
   ```

5. Run the bot:

```
python app.py
```

## Usage

1. Start the bot by messaging it on Telegram.
2. To access the admin panel:
   - Add the bot to a Telegram chat.
   - Promote the bot to an administrator.
   - Send the `/admin` command in the chat.
   - The admin panel will be accessible to all administrators in the chat.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any bugs, feature requests, or improvements.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- This bot is built using the aiogram framework.
- Special thanks to the Telegram API for enabling seamless bot development.
  
---
