---
$title@: Lichnoe-soglashenie-kodirovaniya
author@: Viktor Zharina
$order: 23
$dates:
  published: 2012-09-04 04:28:18
---
<h1>Именование</h1>

varName - переменная

SomeClass - класс

some_method - метод

aArray - массив



<h1>Отступы</h1>

во вложениях условий, циклах - 1 таб

<pre>

for() {

    // some action

}

</pre>

Комментарий - 1 пробел



<h1>Пропуски строк</h1>

Условия и циклы - одна пробельная строка сверху;

Метод - две пробельные строки сверху;

Класс - две пробельные строки сверху;

Группы схожих по смыслу переменных - одна строка сверху;

Комментарий - одна строка сверху



<em>Исключения</em>

<pre>

// some comment

if (condition) {

    // some comment

    if (condition) {

        // some action

    }

}

</pre>



<pre>

for() {

    for() {

        // some action

    }

}

</pre>



<h1>Коды return</h1>

Null - ошибка при выполнении

1 - Ok



<h1>Методы</h1>

Краткое описание метода

Описание входных данных

Описание выходных данных



<h1>Класс</h1>

Краткое описание класса



<h1>Константы</h1>

SOME_CONST



<h1>Префиксы</h1>

g_varName - Глобальные переменные