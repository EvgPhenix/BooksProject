# BooksProject
Проект книжная полка

Технологии проекта
* Maven 3;
* Tomcat8;
* Spring;
* Hibernate;
* MySQL. 

#### CRUD(create, read, update, delete).
Приложение позволяет создавать/добавлять книги в БД, изменять и удалять их.

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

