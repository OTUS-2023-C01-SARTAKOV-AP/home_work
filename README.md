## Раздел посвящён домашним заданиям.

<p> &nbsp; </p>   

В данном разделе выложены домашние задания, выполненные на онлайн курсе “Программист С” компании otus.ru с января 2023 по август 2023 года.

<p> &nbsp; </p>   

**Внимание!!!** Весь код пишется с учётом работы в системе Debian (Linux). Кодировка = ru_RU.UTF-8. &nbsp; &nbsp; &nbsp; БД PostgreSQL имеет кодировку ru_RU.UTF-8.  &nbsp; &nbsp; &nbsp; Переменные внутри кода, пути к файлам (имена папок), названия файлов могут содержать в себе кириллицу (русские буквы). &nbsp; &nbsp; &nbsp; Такая особенность перешла из работы с БД PostgreSQL.

В связи с этим, весь код по разбору входящих данных из терминала работает с широкими символами (два байта информации). Весь код, который анализирует файлы от преподавателей в домашних задачах анализируется как однобайтные символы (все буквы и данные на латинице). В связи с этим многие части кода будут упрощены для работы с однобайтными символами.
В проекте все задачи выполняются исходя из двух байтных символов (широкие символы). Там код будет более сложным.


<p> &nbsp; </p>   

|   фото лето 2021 г.|  успехи |
| ------------ | ------------ |
|  ![](https://github.com/OTUS-2023-C01-SARTAKOV-AP/home_work/blob/main/img/photo_circle_small.png) |<table><tbody><tr><td width="25">№</td><td width="370" align="center">Тема</td><td width="25">Сдано</td></tr><tr><td>01</td><td align="justify">Написать программу, определяющую, является ли заданный файл т.н. Rarjpeg-ом (изображением, в конец которого дописан архив) либо обычным архивом, и выводящую список файлов в архиве, если заданный файл таковым является. Для простоты подразумевается формат архива zip, а не rar. Сторонние библиотеки не использовать.</td><td>да</td></tr><tr><td>02</td><td align="justify"> здесь!!! сли содержимое ячейки выше указанного значения, то данный параметр игнорируется 2___ тема____ тема тема тема и прочие</td><td>&nbsp;</td></tr><tr><td>03</td><td>  3___ тема____ &nbsp;</td><td>&nbsp;</td></tr><tr><td>04</td><td> 4___ тема____  &nbsp;</td><td>&nbsp;</td></tr><tr><td>05</td><td> 5___ тема____  &nbsp;</td><td>&nbsp;</td></tr><tr><td>06</td><td> 6___ тема____  &nbsp;</td><td>&nbsp;</td></tr><tr><td>07</td><td> 7___ тема____  &nbsp;</td><td>&nbsp;</td></tr><tr><td>08</td><td> 8___ тема____  &nbsp;</td><td>&nbsp;</td></tr><tr><td>09</td><td> 9___ тема____  &nbsp;</td><td>&nbsp;</td></tr><tr><td>10</td><td> ___ тема____  &nbsp;</td><td>&nbsp;</td></tr><tr><td>11</td><td> 11___ тема____  &nbsp;</td><td>&nbsp;</td></tr>  <tr><td>12</td><td>  ___ тема____ &nbsp;</td><td>&nbsp;</td></tr>  <tr><td>13</td><td>  ___ тема____ &nbsp;</td><td>&nbsp;</td></tr>  <tr><td>14</td><td>  ___ тема____ &nbsp;</td><td>&nbsp;</td></tr>  <tr><td>15</td><td>  15___ тема____ &nbsp;</td><td>&nbsp;</td></tr>  <tr><td>16</td><td> 16___ тема____ </td><td>&nbsp;</td></tr></tbody></table>|


<p> &nbsp; </p>    
<p> &nbsp; </p>     

----
### Кратко о себе: 

Меня зовут Сартаков Алексей. Живу в г. Нижний Новгород. 

> *   С 2009 года изучал Cache Intersystems. Одновременно с этим активно работал на html, SVG графиках любой сложности.
> *   С конца 2016 года стал изучать PostgreSQL. 
> *   С 2019 стал работать с Python. С 2019 немного Python на стороне БД PostgreSQL. С 2020 много Python на стороне сайта [сайт на голом Питоне (не фрэймворки)]. 
> *   С 2021 изучаю Linux (сам работаю в Debian c 2018 года и она у меня как основная система). Больше меня интересует именно уровень программного обеспечения, а не железа. 
> *   С конца 2021 стал активно изучать Си, т.к. Питон не справлялся с теми задачами, которые на него возлагал (по части БД).  К сожалению, самостоятельно изучить Си не смог (просто не хватало времени). 
> *   Поэтому с января 2023 пошёл на курсы языка Си в образовательную платформу otus.ru. Изучил все что хотел и даже в несколько раз больше. В частности сокеты, распараллеливание задач, окна терминалов, контроллеры, OpenGL. Узнал очень много технической документации. 

Много вывожу сложных графиков через PostgreSQL + html (про возможности приложений на Питоне строить графики знаю и даже немного работал, но столкнулся с рядом закостенелости такой системы и снова вернулся на SVG формат).

На PostgreSQL первые проекты пошли **уже с 2017 года** (в 2016 были просто решения тестовых задач и примеров).



<p> &nbsp; </p>    
<p> &nbsp; </p>          

----
### Умею и знаю:

> 1.  Оптимизация БД PostgreSQL (настройки самого сервера, разбор плана запросов).
> 2.  Разумеется все JOIN , подзапросы, окна, CTE (With ...), группировка, индексы. 
> 3.  BackUp базы данных (автоматически по расписанию через демонов) и её восстановление.
> 4.  Права и роли в PostgreSQL (сайт построен с иерархией ролей по доступу к БД).
> 5.  Логическая репликация. Закачка и разбор данных (в автоматическом режиме) из вне в БД.
> 6.  Регулярные выражения. Сематический разбор текста силами самого PostgreSQL (занимался одно время парсингом/разбором данных с сайтов).
> 7.  Контроль ошибок на стороне сервера (БД) с их занесением в отдельные таблицы с полным описанием проблемы.
> 8.  Плотно работаю с pl/pgSQL (90% кода на нём). 
> 9.  Python, SVG, html (в связке как сайт с запросами к БД, код SVG генерируется на стороне сервера [в PosgreSQL]).
> 10.  Вывод результатов в виде сложных графиков.
> 11.  Администрирование Debian (достаточном для написания скриптов, демонов, ролей, прав).
> 12.  После изучения Си планирую делать большой упор на связку БД PostgreSQL + язык Си. 

<p> &nbsp; </p>   
<p> &nbsp; </p>   

Найти меня можно в телеграмм адресу https://t.me/Sartakov_Aleksey
<p> &nbsp; </p>   
😂 Дата 08 июля 2023 г.
