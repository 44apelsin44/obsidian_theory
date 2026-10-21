`Hyper text transport protocol (secure)`
порт -80(443)
Протокол, по которому мы получаем большую часть ресурсов в интернете, например HTML-документы

Работает на 7 уроввне OSI -протокол общения сервера  и клиента
Протокол легкий, расширяемый,возможно добавлять заголовки 

![Обзор HTTP-запроса GET с заголовками](https://mdn.github.io/shared-assets/images/diagrams/http/overview/http-request.svg)

GET / HTTP/1.1
Host: developer.mozilla.org
Accept-Language: fr


HTTP/1.1 200 OK
Date: Sat, 09 Oct 2010 14:28:02 GMT
Server: Apache
Last-Modified: Tue, 01 Dec 2009 20:18:22 GMT
ETag: "51142bc1-7449-479b075b2891b"
Accept-Ranges: bytes
Content-Length: 29769
Content-Type: text/html

<!doctype html>… (here come the 29769 bytes of the requested web page)

s- secure
https-расширенная версия https c шифрованием tls или устаревшеим ssl поверх TCP 