# Тема проекта. Предсказание рейтинга отеля по данным сайта Booking

## Оглавление  
[1. Описание и цель проекта](./README.md#Описание-проекта)   
[2. Структура проекта](./README.md#Структура-проекта)   
[3. Как установить проект](./README.md#Как-установить-проект)  

### 1. Описание и цель проекта
Имеется датасет, в котором содержатся сведения о 515 000 отзывов на отели Европы. Необходимо качественно подготовить данные (анализ, очистка, проектирование признаков и их преобразование) для обучения модели, которая должна предсказывать рейтинг отеля по данным сайта Booking на основе имеющихся в датасете данных.

### 2. Структура проекта    
Обучение модели для предсказания рейтинга отеля по данным сайта Booking
1. Исследование структуры данных
2. Обучение модели на неподготовленных данных
3. Извлечение информации из строковых данных
4. Очистка от пропущенных значений
5. Преобразование признаков. Кодирование. Нормализация. Стандартизация.
6. Отбор признаков
7. Обучение модели, получение итоговой метрики

### 3. Как установить проект
Выполнить следующие команды в терминале:
1. git clone https://github.com/NadezdaNN/EDA_Hotel_Rating.git
2. Создать виртуальное окружение (в Windows): python -m venv .venv
3. Активировать его (в Windows): .venv/Scripts/Activate.ps1
4. Установить зависимости: pip install -r requirements.txt
