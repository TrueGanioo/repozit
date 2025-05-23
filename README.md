# Проект: Бинарная классификация для предиктивного обслуживания оборудования

## Описание проекта
Цель проекта — разработать модель машинного обучения, которая предсказывает вероятность отказа оборудования (Target = 1) или его нормальную работу (Target = 0) на основе анализа данных. Проект реализован в виде интерактивного Streamlit-приложения, которое позволяет загружать данные, обучать модель, визуализировать результаты и делать предсказания. Это решение предназначено для студентов и специалистов, изучающих предиктивное обслуживание и машинное обучение.

## Датасет
Используется датасет **"AI4I 2020 Predictive Maintenance Dataset"**, доступный в репозитории UCI Machine Learning. Датасет содержит 10 000 записей с 14 признаками, включая:
- **Air temperature [K]**: Температура воздуха.
- **Process temperature [K]**: Температура процесса.
- **Rotational speed [rpm]**: Скорость вращения.
- **Torque [Nm]**: Крутящий момент.
- **Tool wear [min]**: Износ инструмента.
- **Machine failure**: Целевая переменная (0 — нет отказа, 1 — отказ).
Подробное описание датасета можно найти в [документации](https://archive.ics.uci.edu/dataset/601/predictive+maintenance+data).

## Установка и запуск
Используется датасет **"AI4I 2020 Predictive Maintenance Dataset"**, содержащий 10 000 записей с 14 признаками. Подробное описание датасета можно найти в [документации](https://archive.ics.uci.edu/dataset/601/predictive+maintenance+data).

## Установка и запуск
1. Клонируйте репозиторий через командную строку
2. Установка и запуск
## Клонируйте репозиторий:
git clone https://github.com/TrueGanioo/repozit.git 

cd repozit

## Создайте виртуальное окружение:
python -m venv venv

.\venv\Scripts\activate

## Установите все необходимые библеотеки:
 pip install -r requirements.txt
## Запустите приложение:
streamlit run app.py

или откройте окно http://localhost:8501 

## Структура репозитория
app.py: Основной файл приложения.

pages/analysis_and_model.py: Страница с анализом данных и моделью.

pages/presentation.py: Страница с презентацией проекта.

requirements.txt: Файл с зависимостями.

data/predictive_maintenance.csv: Датасет.

README.md: Описание проекта.

video/: Папка для видео-демонстрации (будет добавлено demo.mp4 после записи).
