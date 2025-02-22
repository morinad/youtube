# Коннектор-функция к YouTube Analytics для Power BI и Excel

### Новые видео, статьи и полезности в Telegram-канале: https://t.me/+2kqVrjV5aXs0NTRi

### Все коннекторы и поддержка:
В рамках подписки "ПРО" на Boosty https://boosty.to/morinad вы получите:
1) Все коннекторы mez для Power BI. 
2) Поддержку и ответы на вопросы.
3) Полезные наработки, скрипты и файлы.

### Наши курсы по Power Query, Power BI и автоматизации:
1) Основы Power BI (бесплатный курс): https://directprorf.ru/basics?utm_source=github
2) Power BI для рекламных отчётов: https://directprorf.ru/powerbi?utm_source=github
3) Из API в Excel и Power BI + коннекторы: https://directprorf.ru/excel?utm_source=github
4) Коннекторы для Маркетплейсов: https://directprorf.ru/marketplaces?utm_source=github
5) Продвинутый Power Query: https://directprorf.ru/pro?utm_source=github
6) Создание коннекторов в Power Query: https://directprorf.ru/connectors?utm_source=github


### Как воспользоваться коннектором:
![image](https://github.com/morinad/youtube/assets/44451631/129d9047-bc2a-4514-8ad0-7fd01e9539db)

1. Перейдите по ссылке URL YouTube.
2. После предоставления разрешения в URL появится код, скопируйте его (если не знаете где найти код - смотрите видео по авторизации гугла, оно ниже).
3. Вставьте код в поле authToken.
4. В запросе getRefreshToken появится рефреш токен, скопируйте его.
5. Вставьте рефреш токен в поле refreshToken.
6. Запустите функции YouTubeStat для получения статистики и YouTubeList для получения атрибутов видео.

Подробнее про авторизацию Google в видео по ссылке ниже. В YouTube используется аналогичная авторизация.

### Полезные ссылки:
Видео по авторизации: https://www.youtube.com/watch?v=BPFWkVXFgbo

Получение токена: https://accounts.google.com/ServiceLogin?continue=https://accounts.google.com/o/oauth2/auth?scope%3Dhttps://www.googleapis.com/auth/youtube.readonly%26response_type%3Dcode%26access_type%3Doffline%26redirect_uri%3Dhttp%3A//127.0.0.1%3A9004%26client_id%3D468588465628-rb54ab06irarfvf97jnkit1egd63hog1.apps.googleusercontent.com%26from_login%3D1

Справка API YouTube Analytics: https://developers.google.com/youtube/analytics/reference

Доступные метрики: https://developers.google.com/youtube/analytics/metrics


