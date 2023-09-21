# Инструкция по работе с Git

## Что такое Git?

Git - это распределенная система контроля версий нашего кода. Зачем она нам? Для распределенных команд нужна какая-то система управления работы. Нужна, чтобы отслеживать изменения, которые происходят со временем.

То есть шаг за шагом мы видим, какие файлы изменились и как. Особенно это важно, когда анализируешь, что было проделано в рамках одной задачи: это дает возможность возвращаться назад.

## Настройка Gita

У гита есть настройка пользователя, от которого будет идти работа. Это разумная и необходимая вещь, так как когда создается коммит, гит берет именно эту информацию для поля Author.

Чтобы настроить имя пользователя и пароль для всех проектов, нужно прописать следующие команды:

git config --global user.name "Ivan Ivanov"
git config --global user.email ivan.ivanov@gmail.com

## Слова и действия

- гит репозиторий (git repository);
- коммит (commit);
- ветка (branch);
- смерджить(merge);
- конфликты(conflicts);
- спулить(pull);
- запушить(push);
- как игнорировать какие-то файлы (gitignor).

## 1. Основные команды

git init - инициализация репозитория
git add - добавление файла под версионный контроль
git commit - фиксация изменений
git status - определение состояния файлов
git log - просмотр истории коммитов
git checkout - отмена изменений
git branch - показ существующих веток
git merge - слияние веток 

## 2. Работа с ветками
git branch - показ существующих веток
git branch branch_name - создает ветку с именем branch_name
git checkout branch_name - переключается на ветку с именем branch_name

git branch - показ существующих веток
git checkout -b branch_name - создает ветку с именем branch_name и переключается на нее 

## Работа с удаленными репозиториями в Git - GitHub

git clone <url-адрес репозитория> - клонирование внешнего репозитория на локальный ПК

git pull - получение изменени и слтяние с локальной версией

git push - оптравляет локальнуюверсию репозитория на внешний