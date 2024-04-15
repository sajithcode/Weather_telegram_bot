
---

# Telegram Weather Bot

This is a simple Telegram bot built with Node.js that provides weather information for a given city using the OpenWeatherMap API.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/sajithcode/Weather_telegram_bot.git
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Obtain a Telegram bot token from the [BotFather](https://core.telegram.org/bots#6-botfather) and an API key from [OpenWeatherMap](https://openweathermap.org/) (you'll need to sign up for a free account).

4. Replace `'YOUR_TELEGRAM_BOT_TOKEN'` with your Telegram bot token and `'YOUR_OPENWEATHERMAP_API_KEY'` with your OpenWeatherMap API key in the `index.js` file.

5. Run the bot:
    ```bash
    node index.js
    ```

## How to Use

1. Start a conversation with your bot on Telegram.

2. Send the name of the city for which you want to get weather information.

3. Receive a response with the current weather conditions for the specified city.

## Dependencies

- [node-telegram-bot-api](https://www.npmjs.com/package/node-telegram-bot-api) - Library for interacting with the Telegram Bot API.
- [axios](https://www.npmjs.com/package/axios) - Promise-based HTTP client for making requests to the OpenWeatherMap API.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
