# BooksProject
#### Проект книжная полка

Технологии проекта
* Maven 3;
* Tomcat8;
* Spring;
* Hibernate;
* MySQL. 

Для тестирования использованы:
* JUnit;
* mockito;

#### CRUD(create, read, update, delete).
Приложение позволяет создавать/добавлять книги в БД, изменять и удалять их. Также есть простейшая фильтрация и поиск.

**MYSQL таблица**
* `id`;
* `title` VARCHAR(100);
* `description` VARCHAR(255);
* `author` VARCHAR(100);
* `isbn` VARCHAR(20);
* `printYear` (INT);
* `readAlready` BOOLEAN.
* `image_data mediumblob` for store images in DB.

Для frontend части использованы thymeleaf, bootstrap

Для запуска необходимо открыть в IDEA, запустить MYSQL server, в properties прописать логин и пароль для доступа к БД, выполнить скрипт для наполнения БД информацией и запустить.
