# Проект: Бинарная классификация для предиктивного обслуживания оборудования

## Описание проекта
Цель проекта — разработать модель машинного обучения, которая предсказывает, произойдет ли отказ оборудования (Target = 1) или нет (Target = 0). Результаты работы оформлены в виде Streamlit-приложения.

## Датасет
Используется датасет **"AI4I 2020 Predictive Maintenance Dataset"**, содержащий 10 000 записей с 14 признаками. Подробное описание датасета можно найти в [документации](https://archive.ics.uci.edu/dataset/601/predictive+maintenance+data).

## Установка и запуск
1. Клонируйте репозиторий:
2. Установка и запуск
## Клонируйте репозиторий:
git clone https://github.com/TrueGanioo/repozit.git ;

cd repozit

## Создайте виртуальное окружение:
python -m venv venv

.\venv\Scripts\activate

## Установите все необходимые библеотеки:
 pip install -r requirements.txt
## Запустите приложение:
streamlit run app.py

Откройте http://localhost:8501 в браузере.

## Структура репозитория
app.py: Основной файл приложения.

pages/analysis_and_model.py: Страница с анализом данных и моделью.

pages/presentation.py: Страница с презентацией проекта.

requirements.txt: Файл с зависимостями.

data/predictive_maintenance.csv: Датасет.

README.md: Описание проекта.

video/: Папка для видео-демонстрации (будет добавлено demo.mp4 после записи).
