# EzTelegramBot
чат-бот помощник, позволяющий сконцентрировать кучу разных фич в одном.(до конца еще не готов)

За основу взят https://github.com/python-telegram-bot/python-telegram-bot/blob/master/examples/echobot.py

Пока реализован переводчик(яндекс API) и игра в города.

# Установка

1. Создаем виртуальное окружение и активируем его.
2. Выполняем установку зависимостей:
    >pip install -r requirements.txt

3.Заполнить папку images картинками с расширением .jpg

# Настройка

Создайте файл settings.py и добавте настройки:

>API_KEY = 'API ключ, котоырй вы получили у BotFather'

>TOKEN_FOR_YANDEX_TRANSLATOR = 'токен для работы яндекс переводчика и для использования яндекс-API'

# Запуск

В активированном виртуальном окружении выполните:

>python main.py