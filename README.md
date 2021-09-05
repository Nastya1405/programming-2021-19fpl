﻿**Программирование для лингвистов  3 курс.**

**Основные задачи курса:**

- углубление навыков программирования;
- развитие навыков логического мышления;
- расширение навыков моделирования абстракций;
- улучшение стилевых навыков написания кода;

**Длительность курса:** 1 модуль, 12 занятий, 2 семинара в неделю.

**Содержание учебной дисциплины**: ООП, реализация абстракций (фигуры, база работников), структуры данных (стек, очередь, бинарное дерево поиска).

**Основной стак технологий:** Git + GitHub репозиторий, язык программирования Python 3.x, среда разработки IDE (на выбор), тесты Unittest (or PyTest), линтинг Pylint (or Flake).


**План занятий:**

|Дата|Тема/Работа|
| --- | --- |
|<p>06.09.2021</p><p>ООП</p>|<p>**Семинар**:</p><p>- краткое введение в программу;</p><p>- введение в ООП; презентация первой лабораторной работы по ООП;</p><p>- продумывание интерфейса фигур</p><p>- базовое введение в тесты</p><p>**Результат**:</p><p>- студент знает основные принципы и понятия ООП; </p><p>- студент умеет решать задачи в парадигме ООП;</p>|
|<p>13.09.2021</p><p>Git, стек</p>|<p>**Семинар**:</p><p>- разбор лабораторной работы; вопросы студентов; опрос по ООП</p><p>- работа с git - создание репозитория, форка/клона, коммит, пулл реквест, обновление и слияние;</p><p>- краткое введение в основные понятия теории структур данных и теории алгоритмов (сложность)</p><p>- разбор структуры данных – стек; презентация второй лабораторной работы по стеку;</p><p>- продумывание интерфейса стека</p><p>**Результат**</p><p>- студент умеет работать с git;</p><p>- студент знает основные принципы и понятия теории структур данных;</p><p>- студент знает основную теорию по структуре данных “стек”;</p><p>- студент умеет решать задачи по структуре данных  “стек”;</p>|
|<p>20.09.2021</p><p>Очередь</p>|<p>**Семинар**:</p><p>- разбор лабораторной работы; вопросы студентов; опрос по стеку</p><p>- разбор структуры данных – очередь; презентация третьей лабораторной работы по очереди;</p><p>- продумывание интерфейса очередь</p><p>**Результат**:</p><p>- студент знает основную теорию по структуре данных “очередь”;</p><p>- студент умеет решать задачи по структуре данных “очередь”;</p>|
|<p>27.09.21</p><p>Бинарное дерево поиска</p>|<p>**Семинар**:</p><p>- разбор лабораторной работы; вопросы студентов; опрос по очереди</p><p>- разбор структуры данных – бинарное дерево поиска; презентация четвертой лабораторной работы по бинарному дереву поиска;</p><p>- продумывание интерфейса бинарного дерева поиска</p><p>**Результат**:</p><p>- студент знает основную теорию по структуре данных “бинарное дерево поиска”;</p><p>- студент умеет решать задачи по структуре данных “бинарное дерево поиска”;</p>|
|<p>04.10.2021</p><p>Тестирование</p>|<p>**Семинар**:</p><p>- вопросы студентов; опрос по бинарному дереву поиска</p><p>- теория тестирования: юнит тестирование, сценарное тестирование, стресс тесты;</p><p>- тренировочные задачи по тестированию для упрощения подготовки к лабораторной работе (бинарное дерево поиска);</p><p>**Результат**:</p><p>- студент знает основные принципы тестирования;</p><p>- студент умеет создавать тесты;</p>|
|<p>11.10.2021</p><p>SOLID</p>|<p>**Семинар**:</p><p>- разбор лабораторной работы; вопросы студентов; опрос по принципам тестирования</p><p>- сдача всех долгов по всем работам;</p><p>- выставление оценок;</p><p>- разбор принципов SOLID</p><p>**Результат**:</p><p>- студент знает основные принципы SOLID;</p>|


**Краткий трек занятий:** 1. ООП + лабораторная работа №1, 2. Git, стек + лабораторная работа №2, 3. очередь + лабораторная работа №3, 4. бинарное дерево поиска + лабораторная работа №4, 5. тестирование + лабораторная работа №4, 6. SOLID + подведение итогов;

**Элементы контроля:** 1. Аудиторная работа 2. Лабораторные работы

**Промежуточная аттестация (1 модуль):**
*0.3 \* Аудиторная работа + 0.6 \* Лабораторные работы + 0.1 \* Посещаемость*

*Лабораторные работы = 0.25 \* Лабораторная работа 1 + 0.25 \* Лабораторная работа 2 + 0.25 \* Лабораторная работа 3 + 0.25 \* Лабораторная работа 4*

***Лабораторная работа:***

|   |*4*|*6*|*8*|*10*|
| --- | --- | --- | --- | --- |
|*тесты*|*не проходят (1 или более тестов не проходят - красный Pull Request)*|*тесты проходят (зеленый Pull Request)*|*тесты проходят (зеленый Pull Request)*|*тесты проходят (зеленый Pull Request), **добавлено 3+ индивидуальных тестов***|
|*lint*|*не проходит (lint ниже 10 - красный Pull Request)*|*проходит или не проходит*|*проходит на 10*|*проходит на 10*|
|*просмотр Pull Request*|*весь интерфейс заполнен логикой, программа выдает результат при запуске, возможно некорректный*|*весь интерфейс заполнен логикой, программа выдает корректный результат при запуске, возможно неоптимальное решение*|*весь интерфейс заполнен логикой, программа выдает корректный результат при запуске, оптимальное решение*|*весь интерфейс заполнен логикой, программа выдает корректный результат при запуске, оптимальное решение, стилевая краткость*|

***Оценки 5, 7, 9** ставятся в случае, если студент проявил активность во время выполнения лабораторной работы.*

***Срок выполнения лабораторных работ (с момента объявления лабораторной работы на занятии)** №1 (ООП),2 (стек),3 (очередь) - 1 неделя; №4 (бинарное дерево поиска) - 2 недели. К этому времени ожидается Pull Request в главный репозиторий с зеленым CI. В день сдачи лабораторной работы преподаватель проверяет Pull Request. У студентов, претендующих на повышение оценки, будет три дня для исправлений по комментариям преподавателя в Pull Request (просмотр на третий день, вечером, 20:00).*

**Если лабораторная работа не готова в день сдачи, оценка снижается на 2 балла.**

***Аудиторная работа:***

*плюс ставится за активную работу на занятии (ответы на вопросы, выход к доске, решение задач)*

*10 – 10+ плюсов*

*9 – 9 плюсов*

*8 – 8 плюсов*

*7 – 7 плюсов*

*6 – 6 плюсов*

*5 – 5 плюсов*

*4 – 4 плюса*

*3 – 3 плюса*

*2 – 2 плюса*

*1 – 1 плюс*

*0 – 0 плюсов*


