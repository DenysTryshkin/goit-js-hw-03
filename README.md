**How's your progress with learning arrays and functions? We're sure you'll do great!**

Let's keep climbing to new levels! 🧗‍♂️

By now, you already understand:

-   The principles of how arrays work
-   Basic array methods
-   The specifics of using the `for ... of` loop to iterate over an array
-   The capabilities of working with functions
-   The difference between global and block scope

It's time to put this knowledge into practice and review the previous material.

* * * * *

**Homework: Topic 4. Arrays**

1.  Create a repository named `goit-js-hw-03` and clone it to your computer.
2.  In the `goit-js-hw-03` folder, create the project structure as shown in the diagram below.

**Important!** The file and folder names, as well as their nesting structure, must match the specified scheme. Otherwise, the work will not be accepted.

![](https://s3.eu-north-1.amazonaws.com/lms.goit.files/79c37e44-5578-4a51-854e-e1ea66212537Frame%2048582%20%283%29%20%281%29.jpg)

1.  Read each task and complete it in the corresponding file.
2.  Ensure that the code is formatted using `Prettier`, and that there are no errors or warnings in the console when opening the live page of the assignment.
3.  Submit your homework for review.

**Submission format:**

-   The homework should include two links: one to the repository with the source files and another to the live page hosted on `GitHub Pages`.
-   Attach the repository file in `.zip` format.

☝ **IMPORTANT:**\
Check out the [**instructions on how to download the working file from the GitHub repository**](https://drive.google.com/file/d/1UBw9IkvLmk4hO73ji1ScNkj3_H_vKNvT/view?usp=sharing).

**Grading format:**

-   Pass / Fail

* * * * *

**Task 1. Slug Generator**

Complete this task in the `task-1.js` file.

Before solving the task, let's clarify a new term!

The term **slug** refers to a human-readable unique identifier used in web development to create readable URLs.

For example, instead of having `mysite.com/posts/1q8fh74tx` in the address bar, a slug can be created from the article title. As a result, the URL will be more user-friendly: `mysite.com/posts/arrays-for-beginners`.

**A slug** is always a lowercase string with words separated by hyphens.

Write a function `slugify(title)` that takes the article title as the `title` parameter and returns a slug created from this string.

-   The `title` parameter value will contain strings with words separated by spaces only.
-   All characters in the `slug` must be in lowercase.
-   All words in the `slug` must be separated by hyphens.

Use the code below to check the correctness of your function. The console should output the expected results.

`console.log(slugify("Arrays for beginners")); // "arrays-for-beginners"
console.log(slugify("English for developer")); // "english-for-developer"
console.log(slugify("Ten secrets of JavaScript")); // "ten-secrets-of-javascript"
console.log(slugify("How to become a JUNIOR developer in TWO WEEKS")); // "how-to-become-a-junior-developer-in-two-weeks"`

Leave this code for mentor verification.

**The mentor will check the following:**

-   The function `slugify(title)` is declared.
-   The call `slugify("Arrays for beginners")` returns `"arrays-for-beginners"`.
-   The call `slugify("English for developer")` returns `"english-for-developer"`.
-   The call `slugify("Ten secrets of JavaScript")` returns `"ten-secrets-of-javascript"`.
-   The call `slugify("How to become a JUNIOR developer in TWO WEEKS")` returns `"how-to-become-a-junior-developer-in-two-weeks"`.

* * * * *

**Task 2. Array Composition**

Complete this task in the `task-2.js` file.

Write a function named `makeArray` that takes three parameters: `firstArray` (an array), `secondArray` (an array), and `maxLength` (a number). The function should create a new array containing all elements from `firstArray`, followed by all elements from `secondArray`.

-   If the number of elements in the new array exceeds `maxLength`, the function should return a copy of the array with a length of `maxLength` elements.
-   Otherwise, the function should return the entire new array.

Use the code below to check the correctness of your function. The console should output the expected results.

`console.log(makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3)); // ["Mango", "Poly", "Ajax"]
console.log(makeArray(["Mango", "Poly", "Houston"], ["Ajax", "Chelsea"], 4)); // ["Mango", "Poly", "Houston", "Ajax"]
console.log(makeArray(["Mango"], ["Ajax", "Chelsea", "Poly", "Houston"], 3)); // ["Mango", "Ajax", "Chelsea"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 2)); // ["Earth", "Jupiter"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 4)); // ["Earth", "Jupiter", "Neptune", "Uranus"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus", "Venus"], 0)); // []`

Leave this code for mentor verification.

**The mentor will check the following:**

-   The function `makeArray(firstArray, secondArray, maxLength)` is declared.
-   Various test cases return the expected results.

* * * * *

**Task 3. Filtering an Array of Numbers**

Complete this task in the `task-3.js` file.

Write a function `filterArray(numbers, value)` that takes an array of numbers (`numbers`) and a value (`value`) as parameters. The function should return a new array containing only those numbers from the `numbers` array that are greater than `value`.

Inside the function:

-   Create an empty array to store suitable numbers.
-   Use a loop to iterate over each element of the `numbers` array.
-   Use an `if` statement inside the loop to check each element and add it to your array.
-   Return your new array with suitable numbers as the result.

Use the code below to check the correctness of your function. The console should output the expected results.

`console.log(filterArray([1, 2, 3, 4, 5], 3)); // [4, 5]
console.log(filterArray([1, 2, 3, 4, 5], 4)); // [5]
console.log(filterArray([1, 2, 3, 4, 5], 5)); // []
console.log(filterArray([12, 24, 8, 41, 76], 38)); // [41, 76]
console.log(filterArray([12, 24, 8, 41, 76], 20)); // [24, 41, 76]`

Leave this code for mentor verification.

**The mentor will check the following:**

-   The function `filterArray(numbers, value)` is declared.
-   Various test cases return the expected results.
___________________________________________________________________________
Як успіхи з вивченням масивів та функцій? Ми впевнені, що в тебе все вийде!

Продовжуємо підніматися на нові рівні! 🧗‍♂️

Наразі ти вже розумієш:

-   принцип роботи масивів
-   базові методи масивів
-   специфіку використання цикла `for ... of` для ітерації по масиву
-   можливості при роботі з функціями
-   різницю між глобальною та блоковою областями видимості

Прийшов час на практиці закріпити ці знання та повторити попередній матеріал.

**Домашнє завдання Тема 4. Масиви**

-   Створи репозиторій `goit-js-hw-03` та склонюй його собі на комп'ютер.
-   У папці `goit-js-hw-03` створи структуру проєкта, як показано на схемі нижче.

**Зверни увагу!** Імена файлів та папок, а також їх структура вкладеності, мають відповідати вказаній схемі. В іншому разі робота не буде прийнята.

![](https://s3.eu-north-1.amazonaws.com/lms.goit.files/79c37e44-5578-4a51-854e-e1ea66212537Frame%2048582%20%283%29%20%281%29.jpg)

-   Прочитай кожне завдання і виконай його у відповідному файлі.
-   Переконайся, що код відформатований за допомогою `Prettier`, а в консолі відсутні помилки і попередження під час відкриття живої сторінки завдання.
-   Здай домашнє завдання на перевірку

**Формат здачі:**

-   Домашня робота містить два посилання: на вихідні файли (посилання на репозиторій з кодом) і живу сторінку на `GitHub Pages`.
-   Прикрiплений файл репозиторію у форматi zip

☝ **ВАЖЛИВО**
Переглянь [**Iнструкцію щодо завантаження робочого файлу з репозиторію на Github**](https://drive.google.com/file/d/1UBw9IkvLmk4hO73ji1ScNkj3_H_vKNvT/view?usp=sharing)

**Формат оцінювання:**

-   Залiк / Незалiк

**Задача 1. Генератор slug**

Виконуй це завдання у файлі `task-1.js`

Перш, ніж розв'язувати задачу, давай визначимося із новим терміном!

Термін **slug** --- це зрозумілий людині унікальний ідентифікатор, який використовується у веб розробці для створення читабельних URL-адрес.

Наприклад, замість того, щоб користувач побачив в адресному рядку `mysite.com/posts/1q8fh74tx`, можна зробити `slug` із назви статті. У результаті адреса буде приємнішою для сприйняття: `mysite.com/posts/arrays-for-begginers`.

**Slug** --- це завжди рядок у нижньому регістрі, слова якого розділені тире.

З цим розібралися? А тепер давай нарешті виконувати задачу!

Напиши функцію `slugify(title)`, яка приймає заголовок статті, параметр `title` і повертає `slug`, створений із цього рядка.

-   Значенням параметра `title` будуть рядки, слова яких розділені лише пробілами.
-   Усі символи `slug` повинні бути в нижньому регістрі.
-   Усі слова `slug` повинні бути розділені тире.

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

console.log(slugify("Arrays for begginers")); // "arrays-for-begginers"
console.log(slugify("English for developer")); // "english-for-developer"
console.log(slugify("Ten secrets of JavaScript")); // "ten-secrets-of-javascript"
console.log(slugify("How to become a JUNIOR developer in TWO WEEKS")); // "how-to-become-a-junior-developer-in-two-weeks"

Залиш цей код для перевірки ментором.

**На що буде звертати увагу ментор при перевірці:**

-   Оголошена функція `slugify(title)`
-   Виклик `slugify("Arrays for begginers")` повертає `"arrays-for-begginers"`
-   Виклик `slugify("English for developer")` повертає `"english-for-developer"`
-   Виклик `slugify("Ten secrets of JavaScript")` повертає `"ten-secrets-of-javascript"`
-   Виклик `slugify("How to become a JUNIOR developer in TWO WEEKS")` повертає `"how-to-become-a-junior-developer-in-two-weeks"`

**Задача 2. Композиція масивів**

Виконуй це завдання у файлі `task-2.js`

Напиши функцію під назвою `makeArray`, яка приймає три параметри: `firstArray` (масив), `secondArray` (масив) і `maxLength` (число). Функція повинна створювати новий масив, який містить усі елементи з `firstArray`, а потім усі елементи з `secondArray`.

-   Якщо кількість елементів у новому масиві перевищує `maxLength`, функція повинна повернути копію масиву з довжиною `maxLength` елементів.
-   В іншому випадку функція повинна повернути весь новий масив.

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

console.log(makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3)); // ["Mango", "Poly", "Ajax"]
console.log(makeArray(["Mango", "Poly", "Houston"], ["Ajax", "Chelsea"], 4)); // ["Mango", "Poly", "Houston", "Ajax"]
console.log(makeArray(["Mango"], ["Ajax", "Chelsea", "Poly", "Houston"], 3)); // ["Mango", "Ajax", "Chelsea"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 2)); // ["Earth", "Jupiter"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 4)); // ["Earth", "Jupiter", "Neptune", "Uranus"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus", "Venus"], 0)); // []

Залиш цей код для перевірки ментором.

**На що буде звертати увагу ментор при перевірці:**

-   Оголошена функція `makeArray(firstArray, secondArray, maxLength)`
-   Виклик `makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3)` повертає `["Mango", "Poly", "Ajax"]`
-   Виклик `makeArray(["Mango", "Poly", "Houston"], ["Ajax", "Chelsea"], 4)` повертає `["Mango", "Poly", "Houston", "Ajax"]`
-   Виклик `makeArray(["Mango"], ["Ajax", "Chelsea", "Poly", "Houston"], 3)` повертає `["Mango", "Ajax", "Chelsea"]`
-   Виклик `makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 2)` повертає `["Earth", "Jupiter"]`
-   Виклик `makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 4)` повертає `["Earth", "Jupiter", "Neptune", "Uranus"]`
-   Виклик `makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus", "Venus"], 0)` повертає `[]`
-   Виклик функції `makeArray()` з випадковими масивами і випадковим числом повертає правильний масив

**Задача 3. Фільтрація масиву чисел**

Виконуй це завдання у файлі `task-3.js`

Напиши функцію `filterArray(numbers, value)`, яка приймає масив чисел (`numbers`) та значення (`value`) як параметри. Функція повинна повертати новий масив лише тих чисел із масиву `numbers`, які більші за значення `value`.

Усередині функції:

-   Створи порожній масив, у який будеш додавати підходящі числа.
-   Використай цикл для ітерації кожного елемента масиву `numbers`.
-   Використовуй умовний оператор `if` усередині циклу для перевірки кожного елемента и додавання до свого масиву.
-   Поверни свій новий масив з підходящими числами як результат.

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

console.log(filterArray([1, 2, 3, 4, 5], 3)); // [4, 5]
console.log(filterArray([1, 2, 3, 4, 5], 4)); // [5]
console.log(filterArray([1, 2, 3, 4, 5], 5)); // []
console.log(filterArray([12, 24, 8, 41, 76], 38)); // [41, 76]
console.log(filterArray([12, 24, 8, 41, 76], 20)); // [24, 41, 76]

Залиш цей код для перевірки ментором.

**На що буде звертати увагу ментор при перевірці:**

-   Оголошена функція `filterArray(numbers, value)`
-   Виклик функції `filterArray([1, 2, 3, 4, 5], 3)` повертає `[4, 5]`
-   Виклик функції `filterArray([1, 2, 3, 4, 5], 4)` повертає `[5]`
-   Виклик функції `filterArray([1, 2, 3, 4, 5], 5)` повертає `[]`
-   Виклик функції `filterArray([12, 24, 8, 41, 76], 38)` повертає `[41, 76]`
-   Виклик функції `filterArray([12, 24, 8, 41, 76], 20)` повертає `[24, 41, 76]`
-   Виклик функції `filterArray()` з випадковим масивом і числом повертає правильний масив
