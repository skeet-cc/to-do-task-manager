# Учебный проект: To-Do Task Manager

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
git clone https://github.com/username/todo-task-manager-python.git
cd todo-task-manager-python
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
/todo-task-manager-python
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
- Иван Иванов
- Мария Петрова
- Алексей Смирнов

## 8. Контакты
Email: todo.support@example.com  
GitHub Issues: https://github.com/username/todo-task-manager-python/issues
