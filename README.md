# yandexdrivepodpiskabot
Мониторит какие машины доступны в данный момент для подписки в Яндекс.Драйв по подписке и отправляет в чатик

Сделать 
```
composer install
```

Закинуть в корень .env файл
```
BOT_TOKEN="xxx:yyyy"
BOT_USERNAME="YandexDrivePodpiska"
BOT_CHAT_ID=ТУТ_ИД_ВАШЕГО_С_БОТОМ_ЧАТИКА
```

Запускать
```
php index.php
```
так часто как хочется (лучше через cron)
