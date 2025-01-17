# Основи програамування на Python

### Основні конструкції в Python
1. Створіть Python файл `*.py` або `.ipynb` в якому будете виконувати базові приклади. Застосовуючи команду `print` виконайте наступне:
    1. Познайомтесь з основними [типами даних](https://docs.python.org/3.10/library/stdtypes.html#numeric-types-int-float-complex). Попракитикуйтесь з простими змінними, списками `list`, наборами `set` та словниками `dict`:
       ```python
       a = "змінна з текстом"
       b = 1 # числова Змінна
       c = ["a", 1, 1.25, "Слово"] # List
       d = {"a": "Слово", "b": 1} # Dict
       e = ("a", ) # Set
       ```
    1. Виведіть [вбудовані константи](https://docs.python.org/3.10/library/constants.html), (2-3 на вибір), наприклад:
       ```python
       print("Перша константа", False)
       ```
    1. Виведіть результат роботи [вбудованих функцій](https://docs.python.org/3.10/library/functions.html#func-repr) (2-3 на вибір), наприклад:
       ```python
       print(abs(-12.5), f"є рівним {abs(12.5)}")
       ``` 
    1. Познайомтесь з [циклами](https://docs.python.org/3.10/reference/compound_stmts.html#the-for-statement). Напишіть будь-який код який демонструє роботу циклів, (2-3 на вибір), наприклад:
        ```python
        letters = ["a", "b", "c"]
        for i in range(len(letters)):
            print(f"На позиції {i} знаходиться буква {letters[i]}")
        ```
    1. познайомтесь з [розгалуженнями](https://docs.python.org/3.10/reference/compound_stmts.html#the-if-statement). Напишіть будь-який код який демонструє роботу розгалужень, (2-3 на вибір), наприклад:
       ```python
       A = True
       print("Значить А=True" if A else "Значить А=False")
       ```
    1. Конструкція `try`->`except`->`finally`. У мові Python код не компілюється, а виконується відразу. Можливі помилки нам треба виловлювати самим. Напишіть свій варіант коду з помилкою. Наприклад:
       ```python
       A = 0
       try:
           print("Що буде якщо", 10/A, "?")
       except Exception as e:
           print(e)
       finally:
           print("А вот воно що!")
       ```
    1. Контекст-менеджер `with`. Можете почитати [тут](https://python-scripts.com/contextlib). Напишіть свій код з контекст-менеджером, наприклад:
       ```python
       with open("README.md", "r") as f:
           for line in f:
               print(line)
       ```
    1. Познайомтесь з Python [lambdas](https://docs.python.org/3.10/reference/expressions.html#lambda). Напишіть свій приклад коду та як Ви розумієте Лямбди, наприклад:
       ```python
       this_is_lambda = lambda first, last: f'Цей код написав: {first} {last}'
       print("Це просто функція:", this_is_lambda)
       print("Це її виклик:", this_is_lambda('Богдан', 'Бугиль'))
       ```

### Здача роботи
- :star: коли робота завершена та всі файли завантажено до репозиторію перейдіть у Веб-браузер та скопіюйте URL посилання на вашу роботу;
- :star: відправте URL посилання як відповідь на запитання до завдання у Google Classroom;
- :star: після того як Викладач перевірить роботу, Ви отримаєте оцінку у Google Classroom;
---