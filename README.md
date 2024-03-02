# Примычание:
## dependencies-зависимости
## devDependencies-зависимости в режиме разработки

=================================================


# "dependencies": {
    "bcrypt": "^5.1.1",
    "cors": "^2.8.5",
    "dotenv": "^16.4.1",
    "express": "^4.18.2",
    "express-fileupload": "^1.4.3",
    "jsonwebtoken": "^9.0.2",
    "pg": "^8.11.3",
    "pg-hstore": "^2.3.4",
    "sequelize": "^6.35.2",
    "uuid": "^9.0.1"
  },
# "devDependencies": {
    "nodemon": "^3.0.3"
}
==================================

# Для клиентской части:

## "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-hook-form": "^7.50.0",
    "react-icons": "^5.0.1",
    "react-router": "^6.22.0"
  }
## "devDependencies": {
    "@types/react": "^18.2.43",
    "@types/react-dom": "^18.2.17",
    "@vitejs/plugin-react": "^4.2.1",
    "autoprefixer": "^10.4.17",
    "eslint": "^8.55.0",
    "eslint-plugin-react": "^7.33.2",
    "eslint-plugin-react-hooks": "^4.6.0",
    "eslint-plugin-react-refresh": "^0.4.5",
    "postcss": "^8.4.33",
    "tailwindcss": "^3.4.1",
    "vite": "^5.0.8"
  }
}

==============================

# Для запуска клиетской части: npm run dev

# Для запуска серверной части: npm run dev 


# Примычание:

## Для запуска необходимо установить Node.js и PostgreSQL

## Также есть вероятность ошибки при запуске на вашем устройстве, рекомендуется создать дерективы занова и вставить содержимый код. Также перед действием сделать инициализацию npm init, также для установки всех зависимостей "npm i bcrypt cors dotenv express express-fileupload jsonwebtoken pg pg-hstore sequelize uuid".

## Для клиентской части:
npm create vite@latest
Project name: project-name
>> React
>> JavaScript

## Для установки библиотеки tailwindcss:
https://tailwindcss.com/docs/guides/vite

======================================================

Краткая описание:

# Practical creation of an application for the hotel business/Практическое создание приложения для отельного бизнеса Этот проект сочетает в себе простую систему просмотра и выбору отелей под требования пользователя. Система выбора отелей позволяет пользователям находить подходящие варианты, создавать учетные записи и хранить учетные данные пользователей в базе данных postgreSQL.

## Описание
Сервер для бэкенда
Был изменен скрипт для запуска приложения в режиме разработки.

Папка под названием "server" для серверной части приложения и во взаимодействия с БД.
### Папка "server" включает в себя:
Переменные окружения
Файл прямого подключения
Файл запуска сервера
Зависимости
Файл для api запросов
Файл для маршрутизации
Основные команды
require (можем импортировать в файлы модули)
### Библиотеки и зависимости использованные для серверной части приложения
express (фреймворк)
pg (модуль для СУБД)
pg-hstore (модуль для СУБД)
sequelize (ORM)
cors (для обращения с браузера на сервер)
dotenv (модуль который задает переменные окружения)
nodemon (Дев зависимость для автоматизации запуска сервера при каждом изменений в коде)
