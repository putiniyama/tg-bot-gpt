<p align="center">
  <a href="https://github.com/putiniyama/tg-bot-gpt">
    <img src="https://cdn.midjourney.com/541a73e7-0d79-4600-bc9d-7034e3e39190/0_1.png" alt="logo" width="200" height="165">
  </a>
</p>

<h3 align="center">Telegram bot</h3>

<p align="center">
  Телеграм бот, работает с API openAI. Отвечает на голосовые либо текстовые вопросы.
  <br>
</p>

## Для запуска

- Токен от BotFather;
- Регистрация на openAI;
- Токен от openAI для перевода звуковой дорожки в текст;
- Docker;
- Добавить в папку config файл production.json с токенами:
  {
  "TELEGRAM_TOKEN": "token",
  "OPENAI_KEY": "token",
  "TEXT_ENV": "prod"
  }

## Пуск

- git clone https://github.com/putiniyama/tg-bot-gpt.git
- cd tg-bot-gpt;
- make build;
- make run;
