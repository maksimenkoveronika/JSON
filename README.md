# JSON
JSON
1. Создать внешний репозиторий c названием JSON 
2. Клонировать репозиторий JSON на локальный компьютер  
-----> git clone https://github.com/maksimenkoveronika/JSON.git

3. Внутри локального JSON создать файл “new.json” ----->
----->  cd JSON
	touch new.json

4. Добавить файл под гит
-----> git add new.json

5. Закоммитить файл.
-----> git commit -m "add file"

6. Отправить файл на внешний GitHub репозиторий.
-----> git push

7.Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
-----> vim new.json

      { "name": "NikaMaksimenko",
        "pets": 2,
        "future salary": 1500 }

8. Отправить изменения на внешний репозиторий.
-----> git commit -am "add modify new.json" 
       git push

9. Создать файл preferences.json
-----> touch preferences.json

10.В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON.
-----> vim preferences.json

     {  "Favorite film": "Harry Potter",
        "Favorite series": "Bitten",
        "Favorite food": "Sushi",
        "Favorite time of the year": "Spring",
        "Travel": "England" }

11.Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
----->  touch sklls.json
	vim sklls.json

	{
    "1": "time management skills",
    "2": "abstract and analytical thinking",
    "3": "communication skills",
    "4": "stress tolerance",
    "5": "responsibility",
    "6": "Understanding of software testing and development",
    "7": "Databases",
    "8": "Web technologies",
    "9": "Computer networks",
    "10": "Mobile platforms" }

12. Отправить сразу 2 файла на внешний репозиторий
-----> git add .
       git commit -m "create two files"
       git push

13. На веб интерфейсе создать файл bug_report.json
-----> Add file -> Create new file 

15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

17. Синхронизировать внешний и локальный репозиторий JSON
-----> git pull
