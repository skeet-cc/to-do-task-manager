**To-Do Task Manager**

## 1. Название проекта
**To-Do Task Manager** — лёгкое Python-приложение для ведения списка задач.

## 2. Описание проекта
Приложение позволяет:
- создавать, редактировать и удалять задачи;
- отмечать выполненные пункты;
- сортировать задачи по приоритету или сроку;
- сохранять данные в локальный файл (JSON или SQLite).

## 3. Установка и запуск

### Требования:
- Python 3.10+
- Git
- Windows / Linux / macOS

### Установка:
```bash
git clone https://github.com/skeet-cc/to-do-task-manager
cd to-do-task-manager
python -m venv venv
# Активировать окружение:
# Windows: venv\Scripts\activate
# Linux/macOS: source venv/bin/activate
pip install -r requirements.txt
python main.py
```

## 4. Примеры использования

### Добавление задачи:
```
Введите название задачи: Купить продукты
Введите приоритет: средний
```

### Отметка выполнения:
```
1. Купить продукты — средний — [ ]
2. Написать отчёт — высокий — [ ]
```

## 5. Структура репозитория
```
/to-do-task-manager
│   README.md
│   LICENSE
│   requirements.txt
│
├── src/
│     ├── main.py
│     ├── models.py
│     ├── storage.py
│     └── ui.py
│
└── docs/
```

## 6. Технические требования
- Python 3.10+
- ОС: Windows / Linux / macOS
- Git, редактор кода

## 7. Авторы
- Певнев Александр

## 8. Контакты
aleksandrpevnev572@gmail.com
