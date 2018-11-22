# DEVCIT-JS
Практическая работа №1
======================

## Организация работ

Рекомендуется выделить отдельную директорию для всех практических работ и задач.

### Пример организации директории

```
F:\
|
|--DEVCIT-JS
|----Practice_01_Task_01
|----Practice_01_Task_02
|----...
|----Practice_02_Task_01
|----...
|----URI_Task_1001
|----URI_Task_1002
|----...
```

## Ключевые инструменты разработчика

* [Google Chrome](https://www.google.com/chrome)
* [Visual Studio Code](https://code.visualstudio.com)
* [Node.js](https://nodejs.org/en)

### Альтернативная среда разработки (по желанию)

* [IntelliJ WebStorm](https://www.jetbrains.com/webstorm)

## Задание №0: Первая страница

Создайте статическую HTML страницу с параграфом текста "Привет, Мир!",
любым изображением земли с сайта NASA и ссылкой на эту страницу с текстом
"© NASA".

### HTML элементы

Вам необходимо использовать следующие HTML элементы

* [html](https://developer.mozilla.org/ru/docs/Web/HTML/Element/html)
* [head](https://developer.mozilla.org/ru/docs/Web/HTML/Element/head)
* [meta](https://developer.mozilla.org/ru/docs/Web/HTML/Element/meta)
* [title](https://developer.mozilla.org/ru/docs/Web/HTML/Element/title)
* [body](https://developer.mozilla.org/ru/docs/Web/HTML/Element/body)
* [p](https://developer.mozilla.org/ru/docs/Web/HTML/Element/p)
* [img](https://developer.mozilla.org/ru/docs/Web/HTML/Element/img)
* [a](https://developer.mozilla.org/ru/docs/Web/HTML/Element/a)

## Задание №1: Первая программа

Создайте следующую HTML страницу

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Задание #1</title>
    </head>
    <body>
        <p id="result"></p>
        <script>
            // TODO
        </script>
    </body>
</html>
```

В элементе `</script>` напишите программу, которая выводит сообщение "Привет,
Мир!" в консоль. Создайте альтернативный вариант программы, где сообщение
выводится в пустом элементе `<p>`. Создайте третий вариант программы, где
сообщение выводится в новом диалоговом окне.

### Пример вывода

```
Привет, Мир!
```

* [console](https://developer.mozilla.org/ru/docs/Web/API/console)
* [textContent](https://developer.mozilla.org/ru/docs/Web/API/Node/textContent#Differences_from_innerText)
* [alert](https://developer.mozilla.org/ru/docs/Web/API/Window/alert)

## Задание №2: Сообщение в рамке

Любым способом выведите сообщение вместе с текстовой рамкой, которая состоит
из символов `*`.

### Пример вывода

```
**************
*Привет, Мир!*
**************
```

## Задание №3: Приветствие

Сделайте запрос имени пользователя и выведите приветствие для этого
пользователя. Используйте функцию `prompt(...)` для выполнения задания.

### Пример ввода и вывода

```
Как вас зовут? Дмитрий
Привет, Дмитрий.
```

* [Переменные](https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Grammar_and_Types)
* [prompt](https://developer.mozilla.org/ru/docs/Web/API/Window/prompt)

## Задание №4: Сумма чисел

Сделайте запрос двух чисел у пользователя приложения, найдите их сумму и
выведите значение на экран.

### Форма ввода и вывода

```
Введите первое число: 17
Введите второе число: 25
17 + 25 = 42
```

* [Арифметические операции](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators)

## Задание №5: Калькулятор

Сделайте запрос двух чисел у пользователя приложения, найдите их сумму, разность,
произведение, частное, остаток от деления. Кроме того, возведите первое число в
степень второго числа.

### Форма ввода и вывода

```
Введите первое число: 3
Введите второе число: 5
3 + 5 = 8
3 - 5 = -2
3 * 5 = 15
3 / 5 = 0
3 % 5 = 3
3 ** 5 = 243
```

## Домашнее задание №1: Объем прямоугольного параллелепипеда

Сделайте запрос трёх чисел. Каждое число представляет значение отдельной стороны
параллелепипеда. Найдите объем параллелепипеда и выведите результат на экран.

### Пример вывода

```
Введите значение стороны a: 4
Введите значение стороны b: 3
Введите значение стороны c: 5
Объем параллелепипеда (4 x 3 x 5) равен 60
```

### URI

1. Зарегистрируйтесь на следующем сайте: <https://www.urionlinejudge.com.br/judge/en>
