# Подсказки по Git:

## *Создание репозитория:*
```
Команда: Git init
```

## **Добавление новых изменений в репозитории:**
```
Команда: Git add "Необходимо указать имя репозитория"
```

## _Проверка статуса_
```
Команда: git status
```

## __Комментарий__
1. Команда: Git commit -m "Пишите комментарии который хотите указать" 
    + -m означает что вы указываете сообщение
        - Комментарии нужно оставлять понятно, чтобы пользователь понимал какое именно сообщение вы хотели оставить.

### Команда Git log используется для того чтобы понимать какие изменения были введены и какие комментарии были оставлены другими пользователями.

#### Команда Git checkout используется для того чтобы переключаться между ветками, перемещаться по коммитам, восстанавливать файлы из предыдущих состояний.

Команда git_checkout <имя_ветки>

### Работа с репозиториями
Репозитории бывают открытые и закрытые. Для работы с чужим открытым репозиторием необходимо:
- на github создать fork необходимого репозитория
- выполнить команду *git clone <fork_url>* (желательно по https)
- добавить необходимые файле через команду через *git add <file_name>*
- команда *git pull* позволит получить свежие изменение, если они есть
- выполнить команду *git commit -m "<Комментарий к коммиту>"*
- выполнить команду *git push*
- открыть Git, убедиться в наличии изменений
- перейти в необходимый репозиторий, откуда было сделано ответвление и нажать *Create pull request*
- выбрать интересующие base repository (оригинальный репозиторий) и head repository (ответвление) и сравнить изменения
- добавить комментарий к запросу на слияние и нажать *Create pull request*