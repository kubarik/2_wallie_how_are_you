# Что делает Валли

Код предсказывает, что делает робот-Валли

# Как использовать

Случайным образом выводим текущее состояние робота Валли
```python
action = get_wallie_action()
print (action)
```

Возможные состояния Валли заданы в виде списка:
```python
possible_actions = [
    'считает новых пользователей',
    'готовит новую задачу',
    'что-то проверяет',
    'придумывает новую ачивку',
    'проверяет чью-то задачу',
    'проставляет ссылки в энциклопедии',
    'вычитывает статью',
    'ищет стажировки для студентов',
]
```

Импортируемые модули
```python
import random #функции для генерации случайных чисел, букв, случайного выбора элементов последовательности.
```


# Как запустить и примеры ответа

Скрипт запускается с помощью Python версии 3.x.
Способ установки этого интерпретатора на Windows легко найти в сети Интернет, Google и Яндекс помогут. Скрипт запускается следующей командой:


```#!powershell

> python wallie.py
# Пример ответа
Валли придумывает новую ачивку

```

В Linux Python уже, как правило, установлен, причем сразу в двух вариантах `python2` и `python3`. В таком случае запустить скрипт можно командой

```#!bash

$ python3 wallie.py
# Пример ответа
Валли проверяет чью-то задачу

```


