بالطبع! إليك محتوى ملف README كنص:

---

# Telegram Webhook Bot

This is a simple Flask application that acts as a webhook for a Telegram bot. It listens for incoming updates from Telegram and prints the received data.

## Features

- Receives updates from Telegram using webhook.
- Prints the received JSON data to the console.

## Requirements

- Python 3.x
- Flask

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sifodil/telegrame_webhook.git
   cd telegrame_webhook
   ```

2. Install the required packages:
   ```bash
   pip install Flask
   ```

3. Run the application:
   ```bash
   python app.py
   ```

## Usage

To set up the webhook for your Telegram bot, use the following command:
```bash
https://api.telegram.org/bot<YourBotToken>/setWebhook?url=<YourWebhookURL>
```
Replace `<YourBotToken>` with your bot's token and `<YourWebhookURL>` with the URL of your deployed application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
