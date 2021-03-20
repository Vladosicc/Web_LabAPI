# Web_LabAPI
Лабораторная работа 2

Создание собственного API

1. Разобраться с тем, как работают REST API методы(get, post, put, delete)
2. На 25+: написать простой апи с методами get(есть в примере) и post. Метод get должен выводить все данные без каких либо критериев. Данные выводить на страницу сайта. Данные хранить в структурах данных(списках, картах, массивах). Структуры данных должны содержать объекты(минимум 3).
3. На 35+: написать простой апи с методами get(есть в примере), post, put, delete. Метод get должен выводить все данные без каких либо критериев. Данные выводить на страницу сайта. Данные хранить в структурах данных(списках, картах, массивах). Структуры данных должны содержать объекты(минимум 3).
4. На 45+: написать простой апи с методами get(есть в примере), post, put, delete. Метод get должен получать 1 параметр. Данные выводить на страницу сайта. Данные хранить в файле JSON. Соответственно парсить JSON. Структуры данных должны содержать объекты(минимум 3).

Работу API можно проверить, открыв index.html
Сервер на node.js задеплоин на heroku и доступен по ссылке
https://stankinlab-api.herokuapp.com/
https://stankinlab-api.herokuapp.com/dis/ - url для запросов
https://stankinlab-api.herokuapp.com/get | */post | */put | */delete
Если вдруг heroku не будет работать, то можно проверить, развернув локальный сервер и изменив в script.js первую строчку на локальный адрес сервера
Перезапись файлов на heroku невозможна, так что в json файл новые данные не сохраняются, но так как сервер работает 24/7, новые записи отображаются
Однако при перезапуске все изменения пропадут (можно решить, залив например на heroku MSSQL и хранить все там)
На локальном сервере данные перезаписываются (можно проверить развернув сервер npm start)
Файл с данными server/routes/fromBotforLab.json