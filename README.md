# Проект 0. Угадай число

## Описание проекта
Угадать загаданное компьютером число от 1 до 100 за минимальное количество попыток.  
Алгоритм учитывает подсказки: больше или меньше предполагаемое число относительно загаданного.

## Ссылка на Google Colab
[Открыть в Google Colab](https://colab.research.google.com/drive/1bIk6-C0wZPizE-Dftf77JtIsni29D6c9?usp=sharing)

## Ссылка на файл с данными (если используется)
[Скачать файл с Google Диска](https://drive.google.com/file/d/1bIk6-C0wZPizE-Dftf77JtIsni29D6c9/view?usp=sharing)

## Метрика качества
Среднее количество попыток при 1000 испытаниях. Цель — добиться результата менее 20 попыток.

## Используемые библиотеки
- numpy

## Как запустить проект:
1. Создать виртуальное окружение:
python -m venv venv
2. Активировать:
- Windows: `venv\Scripts\activate`
- macOS/Linux: `source venv/bin/activate`
3. Установить зависимости:
pip install -r requirements.txt