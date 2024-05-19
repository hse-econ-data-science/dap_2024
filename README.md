# Основы программирования на Python, коллекция весна-лето 2024

Этой весной вас ждёт курс по python. Следующей весной будет курс про анализ данных. После каждого из этих курсов будет независимый экзамен от ФКН. Будет, страшно, сложно и весело.

## Важные ссылки:

- Youtube-каналы с записями семинаров: [канал Фила](https://www.youtube.com/playlist?list=PLNKXA-74YGLjMs2d7nk1HbzOcXQz4nQ3y)
- [Таблица с вашими оценками](https://docs.google.com/spreadsheets/d/1mq5ErNkv4vTu5NnjTLPz0EnihGu_VIXaFG6r8UWBejw/edit?usp=sharing)
- Материалы для каждого семинара лежат в папках `/sem*`
- Если вы хотите скачать из репозитория конкретную папку, просто вставьте ссылку на неё [в сервис для скачки.](https://minhaskamal.github.io/DownGit/#/home)
- Любые вопросы можно задавать в общий чат. Там можно найти поддержку и пофлудить. [![TG1](https://img.shields.io/badge/Telegram-chat-blue)](https://t.me/+CHyVKxegN_c3ODZi ) 
- Канал с основными объявлениями [![TG1](https://img.shields.io/badge/Telegram-chat-blue)](https://t.me/+Fcg83yTG9_c5ZTY6)


## Идеология курса

Основная цель курса - научить вас скриптованию. По его итогам вы должны __смело__ уметь открывать python и писать гору кода для решения всех своих проблем. Этот код может быть не очень оптимальным, но рабочим. 

Курс представляет из себя сочетания онлайн и офлайн частей. В офлайн-части, мы на семинарах вместе что-то делаем. В основном решаем задачи. В онлайн-части, вы изучаете дополнительные материалы, которые мы выкладываем и пытаетесь решать задачи. Если что-то не выходит, тербуете консультаций и разбора этих задач у аcсистентов. Они ровно для этого и набраны.

Проверять то, как вы делаете онлайновую часть, мы не будем. Тем не менее, единственный способ научиться программировать - это много программировать. Если вы будете игнорировать онлайновую часть, довольно большой кусок практики выпадет из вашей жизни, а впоследствии на ср и экзамене возникнут проблемы.   


## Домашние задания и контрольные

Тут позже появится список домашек

__Полный список необязательных контестов:__

1. [Типы, строки, числа](https://contest.yandex.ru/contest/48080/problems/)
2. [Условия](https://contest.yandex.ru/contest/48282/problems/)
3. [Цикл for](https://contest.yandex.ru/contest/48284/problems/)
4. [Строки и действительные числа](https://contest.yandex.ru/contest/48286/problems/)
5. [Цикл while](https://contest.yandex.ru/contest/48283/problems/)
6. [Списки](https://contest.yandex.ru/contest/48285/problems/)
7. [Функции](https://contest.yandex.ru/contest/48936/problems/)
8. [Множества](https://contest.yandex.ru/contest/48937/problems/)
9. [Словари](https://contest.yandex.ru/contest/48938/problems/)
10. [Сортировка и линейный поиск](https://contest.yandex.ru/contest/48939/problems/)
11. [Функциональное программирование](https://contest.yandex.ru/contest/48941/problems/)
12. [Классы](https://contest.yandex.ru/contest/48940/problems/)


## Большой план маленьких побед (будет немного меняться)

Установите перед первым семинаром Anaconda. [Инструкция для windows](https://github.com/hse-econ-data-science/dap_2020_fall/blob/master/utils/install_conda_windows.pdf) и [инструкция для мака.](https://github.com/hse-econ-data-science/dap_2020_fall/blob/master/utils/install_conda_mac.pdf)

Anaconda - это дистрибутив для новичка. Обычно рано или поздно от него отказываются. Если вы жёсткий и вам знакомо слово терминал, можно поставить python и всё необходимое через него. Желательно сразу же делать это [через pyenv.](https://github.com/pyenv/pyenv) Более подробная инструкция будет в канале.


- [__sem01__](./sem01_intro) ~~Тратим полтора часа на то, чтобы запустить анаконду.~~ Вводимся в python, git и делаем import this.
- [__sem02&03__](./sem02&03_loops) Говорим про циклы, условия, списки, что такое range (концепция генераторов на пальцах).
- [__sem04__](./sem03_lists_while) Говорим про изменяемые и неизменяемые типы данных: списки, кортежи, строки и методы работы с ними.
- [__sem05__](./sem05_dict) Говорим про словарики и множества. Решаем задачи на словари и множества.
- [__sem06__](./sem06_functions) Говорим о функциях и рекурсии. Решаем задачи на циклы и оформляем их в виде функций.
- [__sem07__](./sem07_files_pandas) Говорим о работе с файлами. Знакомимся с pandas. Решаем задачки с табличками.


## Сдача домашек и контрольных

Сдача части домашних заданий и контрольных будет происходить через  Яндекс.Контест. Для того, чтобы зайти в него вам нужен яндексовый логин. Зарегистрируйте почту на Яндексе и логиньтесь через неё, если у вас ещё нет такой почты.

- [Инструкция как зайти в контест и решить тествое соревнование:](https://github.com/hse-econ-data-science/dap_2020_fall/blob/master/utils/eds_test_contest.pdf)  Инструкция немного устарела. Логиниться надо через яндекс, а не логин с почты.
- [Cсылка на тестовое соревнование](https://contest.yandex.ru/contest/17883/standings)

Другая часть будет сдаваться через anytask. В нём надо будет зарегистрироваться немного позже.


## Самый важный раздел

Вы поулчаете две оценки. Одну за курс, вторую за независимый экзамен. Оценка за курс ставится по формуле: 


```
0.8 * Min(10, 0.1*МСР + 0.25*БСР + 0.3*КР + 0.35*ДЗ)
```

где ДЗ — средняя оценка за все домашние задания (4 штуки), МСР — средняя оценка за все мини-самостоятельные работы на семинарах (около 6 штук), БСР — средняя оценка за все большие самостоятельные работы (3 штуки). Округление арифметическое.

Выше 8 оценку за курс можно получить только перезачётом оценки за независимый экзамен. Информация об этом будет опубликована отдельно в канале курса.


## Лицензия

Весь контент, созданный для этого курса распространяются на правах лицензии [MIT License](https://github.com/hse-econ-data-science/dap_2020_fall/blob/master/LICENSE) либо на правах лицензии [WTFPL](http://www.wtfpl.net/) на ваш выбор. Материалы публикуются как общественное достояние.
