<p></p>

<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №6 <br>
по курсу «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"CSS"</b><p>
<p align="right"><b>Выполнила: </b> студентка 231 группы Витковская Полина</p>
<p  align="right"><b>Принял: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2023</p>
<h2> Введение </h2>
<p>Лабораторные работы по дисциплине «Web-технологии, языки и средства создания web-приложений» предназначены для освоения полученных теоретических знаний на практике. Перед началом лабораторной работы были поставлены цели: <br>
<ol>
  <li>Улучшить навыки работы с CSS стилями, разобраться в иерархии классов и индефикаторов, потренироваться в решении задач с Codewars.
</ol>
В соответствии с данными целями необходимо решить следующие задачи:
<ol>
<li>Создать сайты по образцу.
   <li> Написать скрипты для решения данных задач.
   </ol>
Для реализации данной работы будет использоваться Visual Studio Code. Выполнение кода будет происходить в браузере Google Chrome.
</p>
<h2>Решение задач</h2>
<p>На первой странице были выполнены задачи по CSS: </p>
<code>
div p {}
        div h2 {}
        #test p  {}
        #test h2  {}
        .bbb {}
        #test .bbb  {}
        p.bbb {}
        h2.bbb {}
        #test p.bbb  {}
        .bbb .xxx {}
        p.bbb h2.xxx {}
        #test p.bbb, #test p.xxx {}
        .fff * {}
        .fff p {}
        p.fff {}
        .fff .bbb {}
        .fff h2.bbb {}
        
        #test a:link, #test a:visited {color:red;text-decoration: none;}
        #test a:hover {color:rgb(0, 191, 255);text-decoration:underline;}

        a.www:link,a.www:visited {color:rgb(0, 191, 255);text-decoration:underline;}
        a.www:hover {text-decoration:underline;}

        #test a.www:link, #test a.www:visited {color:rgb(243, 82, 109)}
        #test a.www:hover {color: blueviolet;}

        a.eee:link .www {color:green;} 
   
</code>
<p>Вторая страница была выполнена по образцам из ТХ: </p>
<code>
<style>
        p {margin-left: 20px;}
        div {border:1px gray dotted;margin-bottom: 30px;margin-top: 30px;}
        
    </style>
</head>
<body>
    <div >
    <p style="text-decoration: underline;">Привет, мир!</p>
    <p style="text-decoration:line-through;">Привет, мир!</p>
    <p style="text-decoration:overline">Привет, мир!</p>
    </div>

    <div>
    <p style="width: 200px;height: 200px;border:1px red solid"></p>
    </div>
    
    <div>
    <p style="width: 200px;height: 100px;border:1px blue dotted"></p>
    </div>

    <div>
    <p style="width: 200px;height: 200px;border:1px rgb(5, 116, 29) dotted;border-radius: 40px;"></p>
    </div>

    <div>
    <p style="width: 100px;height: 100px;border:1px rgb(255, 0, 0) solid;border-radius: 100%;"></p>
    </div>

    <div>
        <p><a href="https:/google.com" style="color:green;text-decoration: underline;">Ссылка</a></p> 
        <p><a href="https:/google.com" style="color:red;text-decoration: underline;">Ссылка</a></p>
        <p><a href="https:/google.com" style="color:black;text-decoration: none;">Ссылка</a></p>
    </div>
</body>
</code>
<p>Задачи с ресурса codewars.com:</p>
https://www.codewars.com/users/linariell/completed_solutions
<h2>Вывод</h2>
<p>В ходе лабораторной работы были изучены элементы языка Java script, вновь была проведена работа с CSS. Результатом лабораторной работы являются функции по заданиям</p>
