# Habit Tracker

Проект представляет собой веб-приложение под названием «Habit Tracker», разработанное на основе фреймворка Django. Основная цель данного приложения заключается в помощи пользователям в формировании полезных привычек путем систематического отслеживания их прогресса.

## Технологии

- Python
- Django
- PostgreSQL
- HTML/CSS/JavaScript
- Matplotlib (для построения графиков)

## Основные функциональные возможности

- Создание новых привычек
- Ежедневная фиксация прогресса
- Анализ результатов с помощью графиков и отчетов
- Гибкая настройка сроков и частоты фиксации


<h3>Регистрация и аутентификация:</h3> 
 
- Пользователи могут зарегистрироваться, указав имя, фамилию и пароль.
После успешной регистрации пользователи автоматически авторизуются в системе.

 <h3>Создание привычек:</h3> 

- Авторизованные пользователи могут добавлять новые привычки, указывая только название привычки.
Приложение автоматически устанавливает даты начала и окончания привычки, рассчитанные на 40-дневный период.

<h3>Ежедневная фиксация прогресса:</h3> 

- Для каждой привычки пользователи могут ежедневно фиксировать выполнение или невыполнение задачи.
Прогресс отображается в виде графика, который позволяет визуально оценить динамику выполнения привычки.

<h3>Просмотр списка привычек:</h3> 

- На главной странице авторизованного пользователя отображаются все его активные привычки.
Реализована система пагинации, позволяющая удобно просматривать большое количество привычек.

## Установка и запуск
1. Клонируйте репозиторий:
    - https://github.com/yuriselemin/HABIT_TRACKER.git
2. Установите зависимости:
    - pip install -r requirements.txt
3. Выполните миграцию базы данных:
   - python manage.py migrate
4. Запустите сервер:
   -  python manage.py runserver
  
## Заключение
Habit Tracker является удобным инструментом для формирования новых привычек и улучшения качества жизни пользователей. Простой интерфейс и функциональность отслеживания прогресса мотивируют пользователей достигать долгосрочные цели.


