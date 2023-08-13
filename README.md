1. Создать внешний репозиторий c названием TXT.

 2. Клонировать репозиторий TXT на локальный компьютер. 
    git clone https://github.com/Aliaksandr11/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.
    touch new.txt

 4. Добавить файл под гит.
    git add new.txt

 5. Закоммитить файл.
    git commit -m "commit"
    
 6. Отправить файл на внешний GitHub репозиторий.
    git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
    nano new.txt
    Name: Tsvetkov Aleksandr
    Age: 35
    Pets number: 4
    Salary: 1000$

 8. Отправить изменения на внешний репозиторий.
    git add new.txt
    git commit -m "commit"
    git push

 9. Создать файл preferences.txt
    touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
     Favorite movie: Resident evil
     Favorite serie: Supernatural
     Favorite food: Sweets
     Country visit: Russia

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
     cat >> skills.txt
     1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
     2. Что такое клиент-серверная архитектура.
     3. HTTP Методы запросов на сервер.
     4. Коды ответов HTTP сервера.
     5. Структуры HTTP запросов и ответов.
     6. Что такое JSON, XML. Их структура.
     7. Тестирование API через Postman (JS, автотесты API).
    .....

 12. Сделать коммит в одну строку.
     git add -A && git commit -m "comment"

 13. Отправить сразу 2 файла на внешний репозиторий.
     git push

 14. На веб интерфейсе создать файл bug_report.txt.

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
      
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 18. Синхронизировать внешний и локальный репозиторий TXT
     git pull
  

