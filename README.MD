# Проект "Интернет-магазин"

Запуск проекта:

## Backend
1. cd .\server\
2. node src/app.js

## Frontend
1. cd .\client\
2. node src/main.js

## Настройка проекта
1. Настройка client (Фронтенд)
```cd client```
  Выполнить:
```npm install axios```

2. Настройка server (Бэкенд)
```cd server```
  Выполнить:
```npm install mysql dotenv```

3. В корневой папке проекта создать файлы ```.gitignore``` и ```.env```

# Структура проекта:

# Файлы и папки client (фронтенда)

```client/public/``` - статические файлы, например, изображения, HTML и CSS. Здесь можно разместить ```index.html, styles.css```
---
```client/src/``` - основной исходный код фронтенда.
```components/``` - UI-компоненты, например, ```Header.js, ProductCard.js```
---
```pages/``` - страницы проекта, такие как ```HomePage.js, ProductPage.js```
---
```services/``` - файлы для работы с REST API, например, ```productsService.js, userService.js```, которые экспортируют функции для работы с бэкендом.
---
```main.js``` - основной файл, где подключаются страницы и компоненты.
---
# Файлы и папки server (бэкенда)

```server/src/config/``` - конфигурация базы данных. Создайте ```dbConfig.js```, чтобы настроить подключение к MySQL.
---
```server/src/controllers/``` - контроллеры для обработки запросов API. Например, ```productsController.js, usersController.js```
---
```server/src/models/``` - модели для взаимодействия с базой данных. Например, ```ProductModel.js, UserModel.js```
---
```server/src/routes/``` - файлы маршрутизации, например, ```productsRoutes.js, usersRoutes.js```, чтобы настроить маршруты API.
---
```server/src/middleware/``` - промежуточное ПО для обработки запросов (например, аутентификация, проверка данных).
---
```server/src/utils/``` - вспомогательные функции.
---
# Файлы и папки базы данных (database)

```database/migrations/``` - скрипты миграций для создания и обновления структуры базы данных.
---
```database/seeds/``` - начальные данные для заполнения базы данных
---

![Безымянный](https://github.com/user-attachments/assets/4cc87311-5aab-4b7e-b9ed-fd24f1c0ca11)

