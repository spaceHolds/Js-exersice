# DUT Front-End Dev JS Exercises

**_Riabko Yuliia ISD-12_**

**Exercise 1**

Розв'яжіть усі вирази наведені нижче:

```
5 + "34" --> 534
5 - "4" --> 1
10 % 5 --> 0
5 % 10 --> 5
"Java" + "Script" --> JavaScript
" " + " " --> "  "
" " + 0 --> "0"
true + true --> 2
true + false --> 1
false + true --> 1
false - true --> -1
3 - 4 --> -1
"Bob" - "bill" --> NaN
```

Розв'яжіть усі вирази наведені нижче:

```
5 >= 1 --> true
0 === 1 --> false
4 <= 1 --> false
1 != 1 --> false
"A" > "B" --> false
"B" < "C" --> true
"a" > "A" --> true
"b" < "A" --> false
true === false --> false
true != true --> false
```

Створіть рядок (string): "Привіт! На вулиці "сонячно"" (використовуючи знак +):

```JavaScript

console.log("Привіт! На вулиці" + " " + "сонячно")

```

**Exercise 2**

Розв'яжіть усі вирази наведені нижче:

Додайте змінну "firstName" та "lastName" таким чином, щоб вийшло Ваше повне ім'я

Створіть змінну, у якій збергіається відповідь (повне ім'я) для "firstName" + " " + "lastName"

```JavaScript

const firstName = "Yuliia";
const lastName = "Riabko";

const fullName = firstName + " " + lastName;
console.log(fullName);

```

// Розв'яжіть завдання. Скільки буде a + b?

```JavaScript

var a = 34;
var b = 21;
a = 2;
a + b // --> 23

```

// Чому дорівнює c?

```JavaScript

var c; // --> Undefined

```

**Exercise 3**

Розробіть кальулятор, використовуючи prompt() та змінні. Розробіть программу, яка виконує наступне:

1. Запитує користувача про перший номер
2. Зберігає цей номер
3. Запитує користувача про другий номер
4. Зберігає другий номер та дає відповідь з сумою двох чисел за допомогою alert()

Додатково: Зробіть програму, яка може ділити, множити, та віднімати ці два номери

```JavaScript

const calcFirstNum = prompt("Enter your number", 0);
const calcSecondNum = prompt("Enter your second number", 0);

const calcSum = +calcFirstNum + +calcSecondNum;
alert(`The result of adding this two numbers is ${calcSum}`);

const calcSub = +calcFirstNum - +calcSecondNum;
alert(`The result of subtraction of this two numbers is ${calcSub}`);

const calcMul = +calcFirstNum * +calcSecondNum;
alert(`The result of multiplying this two numbers is ${calcMul}`);

const calcDiv = +calcFirstNum / +calcSecondNum;
alert(`The result of dividing this two numbers is ${calcDiv}`);

```
