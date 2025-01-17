## Основные команды в git
git init – инициализация локального репозитория
git status – получить информацию от git о его текущем состоянии
git add – добавить файл или файлы к следующему коммиту
git commit -m “message” – создание коммита.
git log – вывод на экран истории всех коммитов с их хеш-кодами
git checkout – переход от одного коммита к другому
git checkout master – вернуться к актуальному состоянию и продолжить работу
git diff – увидеть разницу между текущим файлом и закоммиченным файлом

# Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка
(поддерживается 6 уровней).
= или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого
(“=”) и второго (“-”) уровней.
**Полужирное начертание** или __ Полужирное начертание__
*Курсивное начертание* или _Курсивное начертание_
***Полужирное курсивное начертание***
~~Зачёркнутый текст~~
*Строка – ненумерованные списки, символ “*” в начале строки
1, 2, 3 … – нумерованные списки

## РАБОТА С УДАЛЁННЫМИ РЕПОЗИТОРИЯМИ
При запуске команды git init всё происходит только в локальном репозитории: в папке на компьютере пользователя, эту папку создавшего. Но для работы в команде программисты используют удаленные репозитории.
git clone - копировать внешний репозиторий на свой ПК
Она не только загружает все изменения, но и пытается слить все ветки на локальном компьютере и в удаленном репозитории.
git pull - команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией.
git push - отправить свою версию репозитория во внешний репозиторий.
При первом её использовании нужна git pull авторизация.

## Как настроить совместную работу

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории. 
 GitHub при создании нового репозитория подскажет, как это можно сделать
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub),
при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории
5. Провести изменения “с другого компьютера”
6. Выкачать (pull) актуальное состояние из удалённого репозитория

pull request - команда для предложения изменений /
запрос на вливание изменений в репозиторий

## Как сделать pull request
- Делаем   (ответвление) репозитория fork
- Делаем git clone   версии репозитория СВОЕЙ
- Создаем новую ветку и в НЕЕ вносим свои изменения
- Фиксируем изменения (делаем коммиты)
- Отправляем свою версию в свой GitHub
- На сайте GitHub нажимаем кнопку pull request

![The end](LP.jpg)
