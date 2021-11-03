# Рекламент по фронтенду на сборщиках

## Содержание
- [Введение](#intro)
- [Webpack](#webpack)
    - [Установка](#установка)
    - [Команды](#команды)
    - [Структура](#структура)
- [Webpack + Pug](#webpack-pug)
    - [Установка](#установка-1)
    - [Команды](#команды-1)
    - [Структура](#структура-1)

## Введение

На данный момент на проектах используется 2 сборщика – стандартный Webpack и продвинутая сборка с использованием Pug. 

На несложных проектах, или же на проектах с привлечением к верстке джуниоров используем стандартную сборку. Для более серьезных проектов, с прокачанными разработчиками используем расширенную сборку с Pug.

Склонировать ту или иную сборку можно из этой папки, а также перейдя по ссылке в разделе установк.

## Webpack

<img src="https://user-images.githubusercontent.com/22715126/140085371-761753b1-214d-4289-a2f7-9245e2172dbb.png" height="100" title="Webpack" alt="Webpack">

### Установка

- Скачать папку webpack с текущего репозитория
- Перейти на [прямой репозиторий со сборкой](https://github.com/saimon322/webpack-2021) и склонировать проект оттуда

### Команды

Modules install / dev / prod:
    ```shell
    $ npm i
    $ npm start
    $ npm run build
    ```

### Структура

Структура сборки представляет собой полное разделение на компоненты html, стилей и скриптов на стадии разработки и сборку в объединенные файлы на проде.

## Webpack + PUG

<img src="https://user-images.githubusercontent.com/22715126/140085371-761753b1-214d-4289-a2f7-9245e2172dbb.png" height="100" title="Webpack" alt="Webpack">
<img src="https://user-images.githubusercontent.com/22715126/140083253-4e5b9ffa-b339-4f78-b583-7f87535e7d40.png" height="100" title="Pug" alt="Puh">

### Установка

- Скачать папку webpack-pug с текущего репозитория
- Перейти на [прямой репозиторий со сборкой](https://github.com/smiledie-hub/webpack-assembly) и склонировать проект оттуда

### Команды

Modules install / dev / prod:
    ```shell
    $ npm i
    $ yarn dev
    $ yarn build
    ```

### Структура

Структура сборки представляет собой полное разделение на компоненты html, стилей и скриптов на стадии разработки и сборку в объединенные файлы на проде.
