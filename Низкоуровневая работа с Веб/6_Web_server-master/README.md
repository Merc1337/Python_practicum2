## Низкоуровневая работа с веб

### Цель работы

Освоить основные навыки обращения c Web из программы на Python, средства парсинга веб-страниц, соответствующие библиотеки.


1. При ответе вашего сервера посылайте некоторые основные заголовки:
    1. Date
    2. Content-type
    3. Server
    4. Content-length
    5. Connection: close.

![image](https://user-images.githubusercontent.com/51966929/146605859-f277b93a-b2fe-48c7-b5ca-3b2044dd5412.png)

2. Создайте файл настроек вашего веб-сервера, в котором можно задать прослушиваемый порт, рабочую директорию, максимальный объем запроса в байтах. Можете добавить собственные настройки по желанию.

![image](https://user-images.githubusercontent.com/51966929/146605657-2e6f772a-484e-48e7-ad02-fe4606e2039a.png)

3. Если файл не найден, сервер передает в сокет специальный код ошибки - 404.

![image](https://user-images.githubusercontent.com/51966929/146605682-095c8764-9a92-4186-9a02-5d248cc0568c.png)

4. Сервер должен работать в многопоточном режиме.

![image](https://user-images.githubusercontent.com/51966929/146605697-53544dba-7c42-4d03-97c1-c3bea97c3602.png)

5. Сервер должен вести логи в следующем формате: Дата запроса. IP-адрес клиента, имя запрошенного файла, код ошибки.

![image](https://user-images.githubusercontent.com/51966929/146605711-de10f2fd-70c7-43e4-95ea-9ec756c41e81.png)

6. Добавьте возможность запрашивать только определенные типы файлов (.html, .css, .js и так далее). При запросе неразрешенного типа, верните ошибку 403.

![image](https://user-images.githubusercontent.com/51966929/146605727-0d3dfa12-e4f1-454c-8263-18ddbc3d2a0f.png)

7. Реализуйте поддержку постоянного соединения с несколькими запросами.

![image](https://user-images.githubusercontent.com/51966929/146605736-e8e5bbf7-9003-4a09-a178-a04998e10763.png)

(keep-alive)

8. Реализуйте поддержку бинарных типов данных, в частночти, картинок.

![image](https://user-images.githubusercontent.com/51966929/146605765-d7cb39fa-9206-4ff3-b7a0-d706e02dd617.png)


<!-- Docs to Markdown version 1.0β17 -->
