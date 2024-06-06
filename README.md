<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body style="font-family: 'Times New Roman', Times, serif;">
    <p align = "center" style="font-size: 14;">
        МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ <br>
        РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
        ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
        ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
        «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»<br>
    </p>
    <br><br><br><br><br><br>
    <body font-size = "12">
        <p align = "center"> 
            Институт естественных наук и техносферной безопасности<br>
            Кафедра информатики<br>
            Бахтина Елена Владимировна<br>
        </p>
        <br><br><br>
        <p align = "center">
            <strong>Лабораторная работа №8. «JavaScript».</strong><br>
            01.03.02 Прикладная математика и информатика
        </p>
        <br><br><br><br><br><br><br><br><br><br><br><br>
        <p align = "right"> 
            Научный руководитель<br>
            Соболев Евгений Игоревич
        </p>
        <br><br><br>
        <p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
    </body>
    <body style="font-family: 'Times New Roman', Times, serif;">
        <h2 align = "center">Введение</h2>
        <p font-size = "12">
            <b>JavaScript</b> — мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили.
        </p>
        <br>
        <h2 align = "center">Цель и задачи</h2>
        <p align = "left" font-size = "12"> 
            Цель: решить задачи при помощи JS.<br>
            Задачи:<br>
                1.	Напишите оператор if, такой, чтобы в качестве выражения в скобках у него были значения true, false (Например, if( true ) или if( false )). Посмотрите как работает этот оператор, поместив какую-нибудь команду после круглых скобок (Например, console.log(1)). <br>
                2.	Создайте переменные m и n. В m поместите произвольное числовое значение. Напишите оператор ветвления if так, чтобы если m было больше 50, то в переменную n помещалось слово «большое», иначе — слово «маленькое».<br>
                3.	Определите сколько раз выполнится цикл while? Примечание: это можно сделать прочитав скрипт или запустив его консоли браузера.<br>
                <!--var i = 2;
                while( i < 9 ){
                    console.log( i++ );
                }--><br>
                4.	Напишите скрипт, который используя оператор while выведет все числа от 45 до 67.<br>
                5.	Напишите скрипт, который используя оператор while выведет все числа от 45 до 670, кратные 10.<br>
                6.	Напишите скрипт, который используя оператор for выполнит два предыдущих задания.<br>
                7.	Переменная n хранит целое число от 0 до 9. Используя оператор switch, написать скрипт, который в зависимости от числа будет выводить слово (Например, если n равно 3, то будет выводиться слово «три»)<br>
                <!--var n = 5;
                switch( n ){
                //Напишите тут свой код
                }--><br>
                8.	Используя document.write() и любую из циклических конструкций выведите  десять одинаковых изображений (надо выводить <!--<img src="..." alt="..." />-->)<br>
                9.	В переменных size и unit хранятся размер и единицы измерения информации 120 и «Кб» соответственно. Зная что могут быть заданные Кб, Мб, Гб (кило-, мега- и гигабайты) и 1килобайт равен 1024 байта, найти количество байт в size.<br>
                10.	Постройте при помощи циклов JavaScript скрипт для календаря на HTML. Примечание: выполнить задание для одного месяца, используя HTML-элемент table<br>
                11.	Напишите функцию hello1(), которая при вызове будет возвращать строку «Привет, JavaScript!».<br>
                12.	Напишите функцию hello2(), которая при вызове будет принимать переменную name (например, «Василий») и выводить строку (в нашем случае «Привет, Василий»).  В случае отсутствующего аргумента выводить «Привет, гость»<br>
                13.	Напишите функцию mul(n,m), которая принимает два аргумента и возвращает произведение этих аргументов. Проверьте ее работу.<br>
                14.	Создайте функцию repeat(str, n), которая возвращает строку, состоящую из n повторений строки str. n — по умолчанию 2, str — пустая строка<br>
                15.	Создайте функцию rgb(), которая будет принимать три числовых аргумента и возвращать строку вида «rgb(23,100,134)». Если аргументы не заданы, считать их равными нулю. Не проверять переменные на тип данных<br>
                16.	Создайте функцию avg() , которая будет находить среднее значение по всем своим аргументам (аргументы величины числовые).<br>
                17.	Создайте функцию m(a,b) оболочку для mul(). m() должна принимать два аргумента а возвращать результат работы mul() с этими двумя аргументами После выполнения задания поэкспериментируйте, создайте функцию log(), которая будет принимать одно значение, а вызывать  console.log() с этим значением.<br>
                18.	Напишите функцию operation(m,n,o), в которой m и n — числовые переменные, а o — функциональный литерал, который берет два аргумента и выполняет математическую операцию над ними <br>
                19.	Напишите функцию addN(n), которая вернёт другую функцию. Возвращенная функция должна складывать получаемый аргумент с аргументом n возвращающей функции. <br>
                20.	Напишите функцию words(),  которая в зависимости от переданного в нее целочисленного аргумента n, будет выводить слово «товар» в нужной форме («12 товаров», но «22 товара»). По умолчанию аргумент d должен иметь значение 0<br>
                https://www.codewars.com/kata/596fd97f65ad2fc072000037<br>
                https://www.codewars.com/kata/5925138effaed0de490000cf<br>
                https://www.codewars.com/kata/59269e371a640c0e98000085<br>
                https://www.codewars.com/kata/5913ffb2cb1475215c000039<br>

        </p>
        <h2 align = "center">Решение</h2>
        <p font-size = "12">Для выполнения этой лабораторной работы, я пользовалась:</p>
        <p> 1.  Материалом в сети интернет</p>
        </body>
<h3 align = "center">Файл lab8,html</h3>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lab8</title>
    <style>
        .title{ font-weight: bold;}
    </style>
    <style>
        table {
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
        }
        th {
            background-color: #f0f0f0;
        }
    </style>
</head>
<body>
    <div>
        <p class="title">Первое задание:</p>
        <p id="first"></p>
        <button id="btn1">Нажмите</button> <button id="btn2">Нажмите</button>
        <p class="title">Второе задание:</p>
        <p id="second"></p>
        <p class="title">Третье задание:</p>
        <p id="third"></p>
        <p class="title">Четвертое задание:</p>
        <p id="fourth"></p>
        <p class="title">Пятое задание:</p>
        <p id="fifth"></p>
        <p class="title">Шестое задание:</p>
        <p id="Sixth"></p>
        <p class="title">Седьмое задание:</p>
        <p id="seventh"></p>
        <p class="title">Восьмое задание:</p>
        <p id="eight"></p>
        <p class="title">Девятое задание:</p>
        <p id="nine"></p>
        <p class="title">Десятое задание:</p>
            <table id="calendar">
                <thead>
                    <tr>
                        <th>Пн</th>
                        <th>Вт</th>
                        <th>Ср</th>
                        <th>Чт</th>
                        <th>Пт</th>
                        <th>Сб</th>
                        <th>Вс</th>
                    </tr>
                </thead>
                <tbody id="calendar-body"></tbody>
            </table>
        <p class="title">Одинадцатое задание:</p>
        <p id="eleven"></p>
        <p class="title">Двенадцатое задание:</p>
        <p id="twelve"></p>
        <p class="title">Тренадцатое задание:</p>
        <p id="thirteen"></p>
        <p class="title">Четырнадцатое задание:</p>
        <p id="fourteen"></p>
        <p class="title">Пятнадцатое задание:</p>
        <p id="fiveteen"></p>
        <p class="title">Шестнадцатое задание:</p>
        <p id="sixteen"></p>
        <p class="title">Семьнадцатое задание:</p>
        <p id="seventeen"></p>
        <p class="title">Восемьнадцатое задание:</p>
        <p id="eighteen"></p>
        <p class="title">Девятнадцатое задание:</p>
        <p id="nineteen"></p>
        <p class="title">Двенадцатое задание:</p>
        <p id="twenty"></p>
    </div>
    <script>
       function one()
       {
        if (true) {document.getElementById('first').innerText = `${1+1}`;}
       }
       function two()
       {
        if (false) {document.getElementById('first').innerText = `${1+1}`;}
       }
       document.getElementById('btn1').addEventListener('click', one);
       document.getElementById('btn2').addEventListener('click', two);
    </script>
    <script>
        let m = 30;
        let n;
        if (m > 50) {
            n = 'большое';
        } else {
            n = 'маленькое';
        }
        document.getElementById('second').innerText = `${n}`;
    </script>
    <script>
        var i = 2;
        while( i < 9 ){
 	        console.log( i++ );
        }
        document.getElementById('third').innerHTML = `while прошел ${i-2} раз`;
    </script>
    <script>
        let number = 45;
        while (number <= 67) {
            document.getElementById('fourth').innerHTML += ` ${number}`;
            number++;
        }
    </script>
    <script>
        let number1 = 45;
        while (number1 <= 670) {
            if (number1 % 10 === 0) {
                document.getElementById('fifth').innerHTML += ` ${number1}`;
            }
            number1++;
        }
    </script>
    <script>
        for (let i = 45; i <= 67; i++) {
            document.getElementById('Sixth').innerHTML += ` ${i}`;
        }
        for (let j = 45; j <= 670; j++) {
            if (j % 10 === 0) {
                document.getElementById('Sixth').innerHTML += ` ${j}`;            }
        }
    </script>
    <script>
        var a = 5;
        switch(a) {
            case 0:
                document.getElementById('seventh').innerHTML = `Ноль`;
                break;
            case 1:
                document.getElementById('seventh').innerHTML = `Один`;
                break;
            case 2:
                document.getElementById('seventh').innerHTML = `Два`;
                break;
            case 3:
                document.getElementById('seventh').innerHTML = `Три`;
                break;
            case 4:
                document.getElementById('seventh').innerHTML = `Четыре`;
                break;
            case 5:
                document.getElementById('seventh').innerHTML = `Пять`;
                break;
            case 6:
                document.getElementById('seventh').innerHTML = `Шесть`;
                break;
            case 7:
                document.getElementById('seventh').innerHTML = `Семь`;
                break;
            case 8:
                document.getElementById('seventh').innerHTML = `Восемь`;
                break;
            case 9:
                document.getElementById('seventh').innerHTML = `Девять`;
                break;
        }
    </script>
    <script>
        for (var i = 0; i < 10; i++) {
            document.getElementById('eight').innerHTML += ('<img src="https://i.pinimg.com/564x/f4/a4/5c/f4a45c27acc2efb080b8a7d2ca5bd67c.jpg" alt="Image" ' + i + '" />');
        }
    </script>
    <script>
        var size = 120;
        var unit = "Кб";
        var bytes = size;
        switch(unit) {
            case "Кб":
                bytes *= 1024;
                break;
            case "Мб":
                bytes *= 1024 * 1024;
                break;
            case "Гб":
                bytes *= 1024 * 1024 * 1024;
                break;
        }
        document.getElementById('nine').innerText = `Количество байт в размере ${size} ${unit} равно ${bytes} байт.`;
    </script>
    <script>
        const calendarBody = document.getElementById('calendar-body');
        const daysInMonth = 30;
        const startDay = 1;
        let dayCounter = 1;
        for (let i = 0; i < 5; i++) {
            let row = document.createElement('tr');

            for (let j = 0; j < 7; j++) {
                let cell = document.createElement('td');
                if (i === 0 && j < startDay) {
                    cell.textContent = '';
                } else if (dayCounter <= daysInMonth) {
                    cell.textContent = dayCounter;
                    dayCounter++;
                }
                row.appendChild(cell);
            }
            calendarBody.appendChild(row);
        }
    </script>
    <script>
        function hello1() {
            return "Привет, JavaScript!";
        }
        document.getElementById('eleven').innerText = `${hello1()}`;
    </script>
    <script>
        function hello2(name) {
            if (name) {
                return "Привет, " + name;
            } else {
                return "Привет, гость";
            }
        }
        document.getElementById('twelve').innerHTML = `${hello2("Василий")} <br> ${hello2()}`;
    </script>
    <script>
        function mul(n, m) {
            return n * m;
        }
        document.getElementById('thirteen').innerText = `${mul(5,3)}`;
    </script>
    <script>
        function repeat(str = '', n = 2) {
            return str.repeat(n);
        }
        document.getElementById('fourteen').innerHTML = `${repeat('Hello', 3)} <br> ${repeat('🌟', 5)} <br> ${repeat()}`;
    </script>
    <script>
        function rgb(r = 0, g = 0, b = 0) {
            return `rgb(${r},${g},${b})`;
        }
        document.getElementById('fiveteen').innerHTML = `${rgb(23, 100, 134)} <br> ${rgb(255)}`;
    </script>
    <script>
        function avg(...args) {
            if (args.length === 0) {
                return 0;
            }

            const total = args.reduce((acc, cur) => acc + cur, 0);
            return total / args.length;
        }
        document.getElementById('sixteen').innerHTML = `${avg(1, 2, 3, 4, 5)} <br> ${avg(10, 20, 30)} <br> ${avg()}`;
    </script>
    <script>
        function m(a, b) {
            return mul(a, b);
        }

        function log(value) {
            console.log(value);
        }
        const result = m(5, 3);
        log(result); //15
        document.getElementById('seventeen').innerText = `15`;
    </script>
    <script>
        function operation(m, n, o) {
            return o(m, n);
        }
        const addition = function(a, b) {
            return a + b;
        };
        const multiplication = function(a, b) {
            return a * b;
        };
        const result1 = operation(5, 3, addition);
        const result2 = operation(5, 3, multiplication);
        document.getElementById('eighteen').innerHTML = `${result1} | ${result2}`;
    </script>
    <script>
        function addN(n) {
            return function(x) {
                return n + x;
            };
        }
        const add5 = addN(5);
        document.getElementById('nineteen').innerHTML = `${add5(3)} | ${add5(10)}`;
    </script>
    <script>
        function words(n, d = 0) {
            let word = 'товар';
            if (n % 10 === 1 && n % 100 !== 11) {
                word += (d ? 'а' : '');
            } else if ([2, 3, 4].includes(n % 10) && ![12, 13, 14].includes(n % 100)) {
                word += (d ? 'а' : 'ов');
            } else {
                word += (d ? 'ов' : '');
            }
            return `${n} ${word}`;
        }
        document.getElementById('twenty').innerHTML = `${words(1)} <br> ${words(2)} ${words(5, 1)} <br> ${words(22)}`;
    </script>
</body>
</html>
```
</html>
<br>
 <h2 align = "center">Вывод</h2>
 <p align = "left" font-size = "12">
    По итогу данной лабороторной работы, я изучила азы JS и научилась решать базовые задания на этом язке 😊 
</p>
</body>
</html>
