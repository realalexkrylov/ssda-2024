# [Summer school of data analysis 2024 (applied data analysis at HSE)](https://cs.hse.ru/dataschool/2024/)


# MNIST Classifier

Этот проект представляет собой классификатор для распознавания цифр из набора данных MNIST. Он использует сверточную нейронную сеть (CNN) для классификации изображений цифр.

## Описание

Проект включает в себя:
- Создание и обучение модели CNN для классификации цифр.
- Использование PyTorch для реализации нейронной сети.
- Обработку данных и аугментацию для улучшения качества обучения.

## Структура проекта

- `ntogymboys_3.py`: Основной файл с кодом модели и обучения.
- `README.md`: Этот файл, содержащий описание проекта.

## Установка

Для запуска проекта вам потребуется:
- Python 3.x
- PyTorch
- Другие зависимости, указанные в коде.

### Установка зависимостей

Установите необходимые зависимости с помощью pip:

```bash
pip install -r requirements.txt
```

## Использование

1. Установите необходимые зависимости.
2. Запустите файл `ntogymboys_3.py` для обучения модели.

### Пример запуска

```bash
python ntogymboys_3.py
```

## Визуализация

Вы можете использовать TensorBoard для визуализации процесса обучения. Для этого выполните:

```bash
tensorboard --logdir=./logs
```

## Лицензия

Этот проект распространяется под лицензией MIT. 
