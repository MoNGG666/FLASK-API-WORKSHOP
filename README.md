TWIT
1) для запуска программы, нужно открыть терминал в IDE и запустить файл с помощью команды "python main.py", после веденной команды в терменале появиться локальный URL который нужно будет добавть в POSTMAN для изменений и удалений 
2) для проверки работы программы, должна быть устоновленная программа "Postman", и в этой программе создаем две коллекции на (HTTP: 1-я функция будет на "GET", 2-я функция будет на "POST") в данные функции вписываем следующий адрес (localhost:5000/twit)
3) для изменения твита, просмотра и удаления, нужно зайти в функцию (POST-Body-raw и в открывшемся окне добавить наше тело " {"body": "Hello world", "author": "@aqaguy"} ", после добавления можно изменить или удалить эту надпись "Hello world"
