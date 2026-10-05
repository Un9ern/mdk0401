# 🛠️ Технологический стек проекта

Проект разрабатывается с упором на **простоту и скорость разработки**. Весь стек построен исключительно на экосистеме Python, что избавляет от необходимости переключаться между языками и упрощает отладку.

### 🐍 Язык и Бэкенд
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-009688?style=for-the-badge&logo=json&logoColor=white)

### 🗄️ База данных
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### 🎨 Интерфейсы (Frontend)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=for-the-badge&logo=python&logoColor=black)

### 📊 Аналитика и данные
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

### 🛠️ Инструменты разработки
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🎯 Цель разработки

Создать **Web-приложение** (для удаленного доступа и работы через браузер) и **Десктопное приложение** (для локальной работы с большими данными). 

Система должна автоматизировать учет книг, выдачу, возврат и формирование отчетов, заменив ручной труд.

---

## 📋 Роли и обоснование выбора технологий

| Технология | Роль в проекте | Почему выбрана (простота использования) |
| :--- | :--- | :--- |
| **Python** | Язык написания всего кода | Единый язык для бэкенда, фронтенда и аналитики. Не нужно учить JS. |
| **FastAPI** | Создание REST API | Быстрый, легкий, автоматически создает документацию. |
| **PostgreSQL** | Хранение данных | Надежная база данных. Стандарт для подобных задач. |
| **SQLAlchemy** | Связь Python и Базы данных | Позволяет писать запросы на Python, а не на SQL. Код проще читать. |
| **Streamlit** | Web-интерфейс (браузер) | Позволяет сделать сайт на Python без HTML/CSS/JS. Идеально для быстрой разработки. |
| **Tkinter** | Десктопный интерфейс | Встроена в Python. Не требует установки сторонних библиотек. |
| **Pandas** | Обработка данных | Лучший инструмент для фильтрации и создания табличных отчетов. |
| **Matplotlib** | Визуализация | Простой способ нарисовать графики и диаграммы для отчетов. |
| **VS Code** | Среда разработки | Удобный редактор с отличной поддержкой Python. |
| **Git** | Контроль версий | Инструмент для загрузки проекта на GitHub. |

---

## 🏗️ Схема компонентов системы

**1. Клиентская часть:**
*   Web-приложение (доступ через браузер)
*   Десктопное приложение (локальная работа)

**2. Серверный слой (Backend):**
*   FastAPI (Обработка запросов)
*   Модуль аутентификации (Вход в систему)
*   Модуль управления книгами (CRUD)
*   Модуль управления пользователями (Читатели, Библиотекари)
*   Модуль отчетов (Pandas + Matplotlib)
*   SQLAlchemy ORM (Связь с БД)

**3. Слой данных (PostgreSQL):**
*   Таблицы: Books (Книги), Users (Пользователи), Loans (Выдачи), Categories (Категории), Authors (Авторы).

---
