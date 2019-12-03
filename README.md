#FirstSaturdayBot
Бот для Телеграм, который помогает вести учёт изменений для игроков на Ingress FirstSaturday

#Установка бота
0. В Telegram у BotFather создаёте своего бота
1. Создать папку data и дать доступ на запись туда
2. В файле bot.php в строке 4 прописать свой токен, который получен у BotFather

После регистрации бота, нужно сообщить о нём серверу телеграм, установив для данного токена хук с адресом вашего бота.
Сделав это можно, один раз обратившись по адресу
https://api.telegram.org/bot<TOKEN>/setWebhook?url=https://<адрес и путь к скрипту>/bot.php

Удалить установленный хук можно обратившись по адресу
https://api.telegram.org/bot<TOKEN>/deleteWebhook


#Требования
- SSL на хостинге (требуется телеграмм-ом)
- PHP версия 5.4 или старше
- PHP расширение php_xml включено
- PHP расширение php_gd2 включено (если не компилируется)

Был использован краткий синтаксис записи массивов [] вместо array().
Если переписать, требуемая версия PHP опустится до 5.2, необходимой для PHPExcel

#В планах
 - Предусмотреть возможность загрузки профиля не только за всё время, но и за месяц, неделю, день. Придумать как быть и как сравнивать.


