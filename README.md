# TXT
 1. Создать внешний репозиторий c названием TXT.
В шапке сайта слева нажать +, выбрать New repository
В поле Repository name введите TXT, выберите Public и Add a README file.
Нажать Create repository.

 2. Клонировать репозиторий TXT на локальный компьютер.
Нажать Code, выбрать HTTPS, скопировать ссылку на репозиторий, в gitbash зайти в папку, где будет размещен репозиторий),
git clone https://github.com/tsitlau/TXT.git
cd TXT - в терминале перейти в папку TXT, в конце адреса расположения отображается main

 3. Внутри локального TXT создать файл “new.txt”.
touch new.txt

 4. Добавить файл под гит.
git add new.txt

 5. Закоммитить файл.
git commit -m "add new.txt"

 6. Отправить файл на внешний GitHub репозиторий.
git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
vim new.txt
insert
Full name: Tatyana Tsitlau
Age: 33
Number of pets: 1
Desired salary: 900$
Esc
:wq

 8. Отправить изменения на внешний репозиторий.
git add new.txt ; git commit -m " modified new.txt" ; git push

 9. Создать файл preferences.txt
cat > preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
Favorite movie: The Shawshank Redemption
Favorite series: The Beauty Inside
Favorite food: pizza
Favorite time of year: summer
Country_I_want_to_visit: Japan
ctrl+D

 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
cat > skills.txt
1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum.
27. Python. (Изучение основ. Создание клиент серверного приложения)
ctrl+D

 12. Сделать коммит в одну строку.
 13. Отправить сразу 2 файла на внешний репозиторий.
git add preferences.txt skills.txt ; git commit -m "add 2 files" ; git push

 14. На веб интерфейсе создать файл bug_report.txt.
Войти в репозиторий TXT. Нажать кнопку Add file.
Выбрать Create new file. В поле Name your file ввести bug_report.txt

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Нажать кнопку Commit new file

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
Открыть файл bug_report.json Выбрать редактирование. Ввести текст
Bug id: 5
Title: Top and bottom white dash line not visible for size W:242 H:546
Severity: Major
Priority: high
Environment:	Samsung Galaxy s10e, Android 12
	          	Samsung Galaxy М52, Android 11 ONE UI
	           	Samsung Galaxy S8, Android 9.0
	          	Samsung Galaxy Note 8, Android 9.0
	          	Samsung Galaxy A20, Android 11
		          Samsung Galaxy A32, Android 11
		          Samsung Galaxy A7, Android 10
Precondition: Widget on Home screen 4x5
STR:	1. Open app
    	2. Tap the "Add Widget" button
    	3. Tap on the widget, start resizing
AR: When resizing the widget W:242 H:546 the white dash lines above and below are not displayed
ER: When the widget is resized, the white dash lines along the outline are displayed
Attachments: https://disk.yandex.ru/i/J8npWOfTCPP6WA

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Нажать параметр Commit changes

 18. Синхронизировать внешний и локальный репозиторий TXT
git pull
