# -HTTP--REST-

![HTTP-запросы](https://user-images.githubusercontent.com/97500383/155092961-720f3ec8-b62d-4e31-9e7a-819cf0c7b58a.png)

Дополнение к изображению:

Пример запроса: 

GET /index.php HTTP/1.1

Host: example.com
User-Agent: Mozilla/5.0 (X11; U; Linux i686; ru; rv:1.9b5) Gecko/2008050509 Firefox/3.0b5
Accept: text/html
Connection: close

Пример ответа: 

HTTP/1.0 200 OK

Server: nginx/0.6.31
Content-Language: ru
Content-Type: text/html; charset=utf-8
Content-Length: 1234
Connection: close

Здесь обязательными являются стартовые строки, то есть первые строки.

HTTP-методы не обязаны выполнять команду. Поэтому, в помощь приходит REST(REpresentational State Transfer), чтобы методы работали как следует. Тут можно объяснить так: ресурс, в нашем случае index.php - это подлежащее, а метод, в нашем случае GET- это сказуемое. То есть какое действие (метод) мы будем выполнять по отношению ресурса(файла, тут index.php, иногда тут может оказаться и какой-то абстрактный объект, как например blogs/webdev/ и т.д.)
