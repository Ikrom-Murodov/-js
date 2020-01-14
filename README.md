# Gulp 4 - сборка проекта для вёрстки и JavaScript

### Данная сборка предназначена для решения таких задач, как:

- Создание веб-сервера и автоматическая перезагрузка страницы в браузере при сохранении кода, слежение за изменениями в файлах проекта;

- Минификация CSS и JS кода, а также, оптимизация и конкатенация отдельных файлов проекта в один;

- Автоматическое создание вендорных префиксов (приставок к названию CSS свойства, которые добавляют производители браузеров для нестандартных свойств) для CSS.

- Работа с изображениями - сжатие (png, jpg, svg и др.);

> Для работы с Gulp у вас должен быть установлен Node.js. Установка Node.js для различных платформ довольно простая - скачиваете инсталлер Node для своей операционной системы и устанавливаете. Я рекомендую устанавливать последнюю версию Stable

[Вот ссылка для скачивание Node.js](https://nodejs.org/ru/)

> После того, как Node установлен, можно приступать к установке Gulp. Откройте терминал (правая кнопка мыши в папке с зажатым Shift > Откройте здесь оболочку Linux) и выполните следующую команду:

```npm
npm install gulp-cli -g
```

### Инструкция для старта проекта:

> Склонировать данный репозиторий

```git
https://github.com/Ikrom-Murodov/Gulp-4.git
```

> Запустить команду 'npm i' в корне проекта в терминале. Данная команда установит все пакеты, которые указанны в файле package.json, а также все их зависимости

> Команда development запустить веб-сервер и автоматически будет перезагружать страницу в браузере при сохранении кода, и будет следить за изменениями в файлах проекта;

```
gulp development
```

#### Команда для сборки проекта

```
gulp build
```

> Данная команда нужна для сборки проекта на продакшен без лишних файлов, папок и со сжатыми картинками.
