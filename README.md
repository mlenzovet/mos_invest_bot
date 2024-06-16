
# Документация к проекту mos_invest_bot

## Введение

**mos_invest_bot** - это бот для инвестиционных проектов в Москве, разработанный с использованием Jupyter Notebook и HTML.

## Установка

1. Склонируйте репозиторий:
    ```bash
    git clone https://github.com/mlenzovet/mos_invest_bot.git
    ```
2. Установите необходимые зависимости:
    ```bash
    pip install -r requirements.txt
    ```

## Структура проекта

- **static**: статические файлы (изображения, стили).
- **templates**: HTML-шаблоны для веб-страниц.
- **Основные файлы**:  
  - `README.md`: Обзор и инструкции.
  - `Telebot_monolit.ipynb`: Основной скрипт бота.
  - `conversation.ipynb`: Управление диалогами.
  - `csv_test.ipynb`: Работа с CSV.
  - `flask.ipynb`: Интеграция с Flask.
  - `pars_projects_light.ipynb`: Лёгкая версия скрипта для парсинга проектов.

## Подробное описание файлов

### Telebot_monolit.ipynb
**Описание**: Этот ноутбук содержит основной скрипт для работы бота. В нем реализована логика взаимодействия с пользователями, обработка сообщений и команд.

### conversation.ipynb
**Описание**: Этот ноутбук управляет диалогами с пользователями. В нем реализованы сценарии общения и логика ответов на запросы пользователей.

### csv_test.ipynb
**Описание**: Этот ноутбук содержит скрипты для работы с CSV файлами. В нем реализованы функции чтения, записи и обработки данных из CSV.

### flask.ipynb
**Описание**: Этот ноутбук интегрирует бот с Flask для создания веб-интерфейса. В нем реализована логика обработки веб-запросов и рендеринга HTML страниц.

### pars_projects_light.ipynb
**Описание**: Этот ноутбук содержит облегченную версию скрипта для парсинга инвестиционных проектов. В нем реализованы функции для сбора и обработки данных с различных источников.

## static и templates
**Описание**: Директория `static` содержит статические файлы, такие как изображения и стили. Директория `templates` содержит HTML-шаблоны для рендеринга веб-страниц.
