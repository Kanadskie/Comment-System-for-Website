# Система комментирования на JS + Typescript»

ЗАДАЧА ПРОЕКТА

Создать фронтенд-часть для модуля системы комментариев

ФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ

В реализованном проекте можно:
добавлять комментарии. Так как проект не подразумевает создание серверной части, данные можно сохранять в браузере, а для тестирования использовать mock-данные (искусственные данные, имитирующие реальные)
отвечать на уже существующие комментарии
задавать максимальную длину комментария (1000 символов). При превышении этого лимита пользователю запрещается публиковать комментарий (кнопка отправки комментария должна стать неактивной)
изменять рейтинг комментария — увеличивать или уменьшать его на единицу. Каждый пользователь может менять рейтинг строго на единицу (не более). Данные о рейтинге и его изменении можно также хранить в браузере. Прописать это можно в localStorage, чтобы и после обновления страницы было видно, что пользователь уже поменял рейтинг комментария
добавлять комментарий в избранное. После добавления комментария в избранное должны изменяться иконка и текст (макет). При повторном нажатии все изменения отменяются и комментарий перестаёт быть избранным
сортировать все комментарии по различным параметрам — избранные, по дате размещения, количеству оценок, количеству ответов. По умолчанию используйте сортировку по дате размещения

ТРЕБОВАНИЯ К КОДУ

Проект выполнен с использованием TypeScript
На ES6-классах применено ООП
Соблюдено единообразие оформления кода: корректные отступы между смысловыми блоками, единый формат отступов от левого края (два или четыре пробела — на ваш выбор) и так далее
Все переменные, классы и функции имеют осмысленные имена
Проект следует принципам DRY (Don’t Repeat Yourself) и KISS (Keep It Short and Simple).
Все комментарии хранятся в localStorage
Проект должен хранить все зависимости в себе и не иметь никаких глобальных зависимостей, кроме NodeJS и NPM

ТРЕБОВАНИЯ К ИНТЕРФЕЙСУ

Дизайн итогового проекта должен полностью соответствовать исходному макету

КАК ЗАПУСТИТЬ ПРОЕКТ

Запустить в консоле команду npm run build-tsc для компиляции файла index.ts (папка src) в index.js (папка build), после запустить в консоле команду npm run build-webpack для сборки bundle

Открыть файл index.html в корневой папке проекта

