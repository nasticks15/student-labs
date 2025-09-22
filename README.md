# student-labs
# Лабораторна робота №1  
**Тема:** Вступні заняття: налаштування середовища, початок роботи з Python та Markdown  

---

## Мета роботи
- Налаштувати середовище VS Code.  
- Встановити потрібні плагіни (Python, Jupyter, Copilot).  
- Написати першу програму на Python.  
- Спробувати роботу з Jupyter Notebook.  
- Оформити звіт у форматі Markdown та завантажити його у GitHub.  

---

## Виконання роботи

### 1. Створення структури
У репозиторії створена папка **1_lab**, у якій знаходяться:  
- `my_first_app.py`  
- `my_first_app.ipynb`  
- `README.md` (цей файл)  
- `screenshots/` (зі скріншотами запуску)  

---

### 2. Перша програма (`my_first_app.py`)
```python
from datetime import datetime

name = "Anastasiia"
location = "Lviv"

print(f"{name} start programming at {datetime.now()}. {location} is the best city!")
