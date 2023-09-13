# Руководство пользователя по работе с Git
## Основные команды 
* git init-инициализирует репозиторий
* git merge < branch> - слияние веток
* git diff - просмотр изменённых файлов
* git log - история commitov 
* git status - определение состояния файлов
* git push - отправка ветки
* git checkout - переход на ветку


## Работа с удалённым репозиторием
* git remote - отоброжение удалённых репозиториев
* git remote add <alias> <remote> - добавление удалённых репозиториев
* git remote show <remote> - информация об удалённом репозитории
* git push < remote> <branch> - отправление локальных изменений на удалённый сервис
* git remote show <old name> < new name> - переименновывание удалённых репозиториев
* git pull <remote> <branch> - получение данных из удалённого репозитория и слияние с локальным
* git fetch <remote> - получение данных из удалённых репозиториев
* git remote rename < old name> < new name> - переименовывание удалённых репозиториев
* git remote rm < remote> - удалёние удалённых репозиториев