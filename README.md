#CWP/TASK/33 - Деплой
function task00() {

Создаем на Github репозиторий cwp-33-cli, клонируем его, открываем в IDE

Копируем файлы из cwp-32

Устанавливаем heroku cli

Опубликуем проект на Heroku используя командную строку

}

function task01() {

Создаем на Github репозиторий cwp-33-cd, клонируем его, открываем в IDE

Копируем файлы из cwp-32

Устанавливаем sequelize

Перенесём хранение данных из оперативной памяти в базу данных

Сконфигурируем сервер для использования локальной БД при локальном запуске и БД на Heroku (postgre) при запуске на сервере. Для этих целей отлично подойдут переменные окружения

Настроим автоматическую публикацию проекта с Github на Heroku

}

function task02() {

Создаем на Github репозиторий cwp-33-pm, клонируем его, открываем в IDE

Устанавливаем express, bcryptjs, uuid, siege и pm2

В файле index.js напишем express-сервер, который по пути /hash будет отдавать хэш от uuid/v4. Количество циклов bcrypt установим в 10.

В файле benchmark.js напишем нагрузочный тест с помощью siege. Нагрузку будем подавать в течении 120 секунд и 50 параллельными запросами.

Запустим сервер и тест. Запишем результаты

С помощью pm2 запустим сервер в кластерном режиме с количеством потоков равным количеству ядер процессора. Запустим тест и сравним результаты

}