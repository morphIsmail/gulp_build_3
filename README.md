# Сборка проекта на Gulp 4, Версия 3

## Описание проекта: 
С помощью этих файлов вы сможете быстро настроить сборку вашего проекта на Gulp. 

## Модули:
    "browser-sync": Синхронизация кода с результатами в браузере
    "del": Удаление каталогов и файлов
    "gulp": Сборщик Gulp
    "gulp-autoprefixer": Добавляет префиксы в CSS код
    "gulp-clean-css": Минификация и оптимизация CSS файлов 
    "gulp-concat": Объединение нескольких файлов в один
    "gulp-imagemin": Для сжатия изображений
    "gulp-less": Компиляция Less файлов
    "gulp-rename": Переименовывает файлы
    "gulp-sass": Компиляция Sass и Scss файлов
    "gulp-sourcemaps": Для работы с препроцессорами, создает карту кода для консоли в браузере
    "gulp-stylus": Компиляция Stylus файлов 
    "gulp-uglify": Сжатие и оптимизация Java Script кода

## Структура файлов и папок:  
>./src  
>>	/css  
>>>		/*.scss *.sass *.less *.styl *.css 
>>>		/*.scss *.sass *.less *.styl *.css 
>> /img  
>>	/js  
>>>		/lib.js  
>>>		/main.js  
>./gulpfile.js  
>./package.json  
>./index.html  

## Инструкция:  
1. Скачать все файлы в любую директорию   
2. Ввести в терминале/командной строке команду: npm i (должен быть установлен node.js) 
3. Выполнить команду: gulp (запуск таска default, который очистит каталог build и запустит таск scripts, styles и img-compress, а так же watch - отслеживает изменения в файлах html, css, sass, scss, less, styl, js и в каталоге img) 
4. Писать свой код и наслаждаться автоматической сборкой проекта. 

---

[![GitHub](https://img.shields.io/badge/-Мой_GitHub-333?style=for-the-badge&logo=GitHub&logoColor=fff)](https://github.com/morphIsmail)