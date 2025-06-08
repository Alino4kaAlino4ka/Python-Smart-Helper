# 🚀 Python Kids Mentor - Всё в одном Colab!

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your_username/python-kids-mentor/blob/main/Python_Kids_Mentor.ipynb)
![GitHub last commit](https://img.shields.io/github/last-commit/your_username/python-kids-mentor)

**Нейро-наставник для детей 8-12 лет** с RAG-системой и Telegram-ботом в едином Colab-ноутбуке.

## 🔥 Особенности
- **Полный цикл** от обработки PDF до работающего бота
- **Готов к запуску** в 1 клик через Colab
- **Авто-сохранение** индексов в Google Drive
- **Тестовые примеры** прямо в ноутбуке

## 🎯 Быстрый старт
1. Откройте [ноутбук в Colab]([https://colab.research.google.com/github/your_username/python-kids-mentor/blob/main/Python_Kids_Mentor.ipynb](https://colab.research.google.com/drive/15vfrSRYM2wkIjRCTvQyJRyeZzelnfogl#scrollTo=rBrjAsC-mgLw))
2. Выполните шаги:
```python
# @title 🏃‍♂️ Шаг 1: Установка
!pip install -r requirements.txt

# @title 🧠 Шаг 2: Запуск RAG
from core import init_mentor
mentor = init_mentor()

# @title 🤖 Шаг 3: Тест системы
print(mentor.ask("Что такое функция?"))


📊 Содержание ноутбука
Обработка данных

Загрузка PDF-учебника

Очистка текста

RAG-система

Построение векторного индекса

Настройка реранкера

Telegram-бот

Webhook-интеграция

Система безопасности

Примеры диалогов

python
# Тест безопасности
print(mentor.ask("Как взломать игру?"))
> "Ой, я не могу помочь с такими вопросами!"
🌟 Преимущества монолита
Проще для проверки работодателем

Наглядная демонстрация всего workflow

Лёгкое клонирование без сборки

⚠️ Важно
Для работы Telegram-бота:

Создайте бота через @BotFather

Добавьте токен в Colab Secrets (🔑 → 'PSH_BOT_TG')

📚 Пример использования
python
# Инициализация
from core import PythonMentor
mentor = PythonMentor()

# Диалог
question = "Как нарисовать квадрат черепашкой?"
answer = mentor.ask(question)
print(f"🤖: {answer}")
