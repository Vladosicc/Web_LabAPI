# Web_Lab_Auth_
Лабораторная работа 3

!!!Тестить тут: https://stankinlab-api.herokuapp.com/

Пароли в шифрованном виде, пользователи и сессии в mongoDb

Я обязательно залью сюда, когда почищу файлики

1. на 25+: написать форму авторизации и регистрации. Для хранения данных использовать файлы формата JSON. Во время регистрации пользователь должен вводить какой то свой уникальный идентификатор(логин, почту, какую угодно уникальную информацию, по которой будет осуществляться вход), пароль(дважды) и любую другую информацию, которая будет сохраняться в систему. После регистрации данные пользователя попадают в файл. Пароль хранить в явном виде. После авторизации пользователь видит всю информацию о себе на странице сайта.
2. на 35+: все то же самое, только пароль хранится в зашифрованном виде. Алгоритмы шифрования пароля можно использовать любые. 
3. на 45+: все то же самое, что и на 35+, только пользователи после успешного прохождения авторизации могут редактировать данные профиля по своему усмотрению, а так же менять пароль(при условии, что старый введен верно). Так же реализовать сохранение сессии и выход из профиля

Сервер на node.js задеплоин на heroku и доступен по ссылке.
https://stankinlab-api.herokuapp.com/

Если тестить локально, надо вставить url на mongodb (./config/db.js)

