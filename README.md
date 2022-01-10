# Challenges_Lab5
## Toxic
![1](/ЗИ_Challenges/Toxic/nothing_on_website.png)
### На странице нет ничего интересного
![1](/ЗИ_Challenges/Toxic/coded_in_base64.png)
### Смотрим файлы к челенджу, находим в файле index.php, что куки сессии закодировван в base_64
![1](/ЗИ_Challenges/Toxic/cookie.png)
### Достаем куки сессии
![1](/ЗИ_Challenges/Toxic/decoded_cookie.png)
### Декодируем куки
![1](/ЗИ_Challenges/Toxic/payload.png)
### Поменяем куки чтобы посмотреть логи
![1](/ЗИ_Challenges/Toxic/request.png)
![1](/ЗИ_Challenges/Toxic/response.png)
### Получили в ответе папки, среди них главный инетерес сосавляет папка с флагом
![1](/ЗИ_Challenges/Toxic/payload2.png)
### Пытаемся в нее зайти
![1](/ЗИ_Challenges/Toxic/key.png)
### Ура! Мы это сделали!
![1](/ЗИ_Challenges/Toxic/done.png)

## USB Ripper
![1](/ЗИ_Challenges/USB_Ripper/usb-ripper_catalog.png)
### Вот что идет в комплекте с этим челленджем
![1](/ЗИ_Challenges/USB_Ripper/manufact_json.png)
![1](/ЗИ_Challenges/USB_Ripper/serial_num.png)
![1](/ЗИ_Challenges/USB_Ripper/product_num.png)
### Json файл
![1](/ЗИ_Challenges/USB_Ripper/syslog.png)
### log взломанной машины
![1](/ЗИ_Challenges/USB_Ripper/python_script.png)
### Ищем серийный номер в логах такой, чтобы его не было в джейсоне
![1](/ЗИ_Challenges/USB_Ripper/serial_found.png)
![1](/ЗИ_Challenges/USB_Ripper/md5_decode.png)
### Декодируем и получаем флаг
![1](/ЗИ_Challenges/USB_Ripper/succ.png)

## MarketDump
![1](/ЗИ_Challenges/MarketDump/description.png)
### Злоумышленник украл бд. Окей
![1](/ЗИ_Challenges/MarketDump/files.png)
### Единственный файл - это перехваченные пакеты
![1](/ЗИ_Challenges/MarketDump/how.png)
### Гуглим как его открыть
![1](/ЗИ_Challenges/MarketDump/tracer_res.png)
### Ищу что связано с базами данных отсортировав по протоколу и обращаю внимание только на протоколы HTTP
![1](/ЗИ_Challenges/MarketDump/res.png)
### В хедере написано что запрос был к базе, мб наш человек?
![1](/ЗИ_Challenges/MarketDump/key.png)
### Немного полистав файл видим что то странное
![1](/ЗИ_Challenges/MarketDump/decoded.png)
### Пытаемся декодировать, и, действительно, все получилось
![1](/ЗИ_Challenges/MarketDump/done.png)
