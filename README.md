# jsbymdahw11
JS by MDA. Homework to lesson #11

## Задачи

1. Создать функции login() и logout(). 
2. Когда Вы авторизуетесь: "Войти". Когда Вы авторизованы: "Выйти".
3. Нужна функция checkLogin(), чтобы "Войти" поменять на "Выйти".
4. Использовать location.reload(true) для функций login() и logout(). Это нужно для выполнения процесса перезагрузки страницы.
5. Подумать: как при авторизации изменить цены на товар в корзине.

## Замечания
1. Замечание 1.
2. Замечание 3.



## Подсказки и ценные указания
1. [tip #1](https://youtu.be/q8GNmuEvzRU)
2. Для firebase необходимо указать в строке URI формат файла json
```
fetch('https://project-d68d1-default-rtdb.firebaseio.com/db.json')
```
Для получение данных локально из файла db.json необходимо включать Live server.

3. Для передачи ошибки в метод .catch необходимо передать сам объект и его свойство status
```
fetch('https://project-d68d1-default-rtdb.firebaseio.com/db.json')
  .then(response => {
    if (response.status === 200) {
      return response.json();
    } else {
      throw new Error(response.status)
    }
  })
  .then(data => {
    localStorage.setItem('cards', JSON.stringify(data))
  })
  .catch(error => {
    console.log(error.message);
  })
```

## Решение
### 1 Задача 1:
* Шаг 1

* Шаг 2

* Шаг 3

* Шаг 4

* Шаг 5

### 2 Задача 2:
* Шаг 1

* Шаг 2

* Шаг 3

* Шаг 4

* Шаг 5

### 3 Задача 3:
* Шаг 1

* Шаг 2

* Шаг 3

* Шаг 4

* Шаг 5

### 4 Задача 4:
* Шаг 1

* Шаг 2

* Шаг 3

* Шаг 4

* Шаг 5

### 5 Задача 5:
* Шаг 1

* Шаг 2

* Шаг 3

* Шаг 4

* Шаг 5