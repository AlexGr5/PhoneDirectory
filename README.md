Для запуска приложения необходимо подготовить БД.

1) Создать БД в PostgreSQL с любым именем
2) Восстановить новую БД из файла phone_copy.sql
3) Ввести новые данные в файл application.properties (название БД, имя и пароль от БД)


Для использования программы, необходимо разархивировать архив all_work.rar и запустить проект в Intellij IDEA. 


Или ссоздать spring boot приложение на сайте https://start.spring.io/

После скачивания нового проекта, перенести файлы из этого репозиторя в новый:

1) Каталоги: Controllers, dao, forbd, models в каталог main->src...(в самую глубь)
2) Из файла pom.xml скопировать в новый или заменить, обновить ресурсы maven
3) Все каталоги из templates скопировать в новый templates прокта или заменить


Должно заработать.
