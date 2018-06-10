# Cognitive Cake's portfolio

## Рабочие проекты

* ### Cайт небольшого деревообрабатывающего производства.

    Адаптивная вёрстка.

    Переписывание сайта с Wix на Bootstrap.
Проект не был принят заказчиком. Под конец проекта заказчик решил сделать редизайн и мой рефакторинг оказался не нужен.


    * [Страница проекта](https://cognitive-cake.github.io/pictor/)  
    * [Репозиторий](https://github.com/cognitive-cake/pictor)

## Личные проекты, учебные проекты

* ### Личный проект, работаю над ним в свободное время. Вёрстка лендинга с двумя слайдерами и canvas (слайдеры ещё не завершены).

    Вёрстка и JavaScript. Bootstrap, ES6 и Babel.

    * [Страница проекта](https://cognitive-cake.github.io/landing-giant-app/)   
    * [Репозиторий](https://github.com/cognitive-cake/landing-giant-app)

* ### NPM-пакет "Вычислитель отличий" (проект с [Hexlet.io](https://hexlet.io)).

    JavaScript. ES6, Babel, Node.js, NPM, Jest, TDD, CI.

    В рамках данного проекта необходимо было реализовать утилиту для поиска отличий в конфигурационных файлах.

    Текущие возможности утилиты:

    * Поддержка как плоских, так и вложенных json, yaml, ini
    * Генерация отчёта в виде Pretty, Plain, Json
    * Возможность использовать пакет как библиотеку

    Пример использования:

    ```
    > $ gendiff before.json after.json                            
    common: {
        setting1: Value 1
      - setting2: 200
      + setting3: {
            key: value
        }
      - setting3: true
        setting6: {
            key: value
          + ops: vops
        }
      + setting4: blah blah
      + setting5: {
            key5: value5
        }
    }
    group1: {
      + baz: bars
      - baz: bas
        foo: bar
      + nest: str
      - nest: {
            key: value
        }
    }
    ```

    * [Страница проекта](https://www.npmjs.com/package/gendiff-cake)
    * [Репозиторий](https://github.com/cognitive-cake/project-lvl2-s269)    

* ### NPM-пакет Brain Games (проект с [Hexlet.io](https://hexlet.io)).

    JavaScript. ES6, Babel, Node.js, NPM.

    В рамках проекта необходимо было реализовать набор мини-игр, запускаемых из консоли. Эти игры похожи на то, что обычно называют "Brain Games".  

    Пример игры:

    ```
    Welcome to the Brain Games!

    What number is missing in this progression?

    May I have your name? John
    Hello, John!

    Question: 14 .. 18 20 22 24 26 28
    Your answer: 16
    Correct!
    Question: 5 6 7 8 9 .. 11 12
    Your answer: 10
    Correct!
    Question: 12 15 18 21 .. 27 30 33
    Your answer: 24
    Correct!
    Congratulations, John!
    ```

    * [Страница проекта](https://www.npmjs.com/package/braingames-cake) 
    * [Репозиторий](https://github.com/cognitive-cake/project-lvl1-s220)


* ### Простенький макет с 5-ю брейкпоинтами на флексбоксах

    Только вёрстка.

    * [Страница проекта](https://cognitive-cake.github.io/simple-adaptive-site/)  
    * [Репозиторий](https://github.com/cognitive-cake/simple-adaptive-site)


* ### Учебный проект по JS в HtmlAcademy: Сервис просмотра изображений.

    Только JavaScript.

    Реализованные особенности: Загрузка изображений пользователя, обработка изображения с помощью фильтров, валидация формы отправки изображения. Работа через AJAX с сервером, получение данных об изображениях и добавление их в DOM, сортировка миниатюр, показ модульного окна с увеличенной версией миниатюры.

    * [Техническое задание](https://github.com/cognitive-cake/kekstagram/blob/master/Specification.md)  
    * [Страница проекта](https://cognitive-cake.github.io/kekstagram/)
    * [Репозиторий](https://github.com/cognitive-cake/kekstagram)


* ### Учебный проект по HTML и CSS в HtmlAcademy: Сайт магазина изделий ручной работы.

    Только вёрстка.

    Реализованные особенности: Адаптивная, кроссбраузерная вёрстка c использованием Flexbox и без использования фреймворков. В проекте используется методология БЭМ, препроцессор SASS и таскраннер Gulp. Применяется ретинизация изображений и SVG вместо иконочных шрифтов.

    * [Техническое задание](https://github.com/cognitive-cake/mimimishka/blob/master/Specification.md)
    * [Страница проекта](https://cognitive-cake.github.io/mimimishka/)
    * [Репозиторий](https://github.com/cognitive-cake/mimimishka)
