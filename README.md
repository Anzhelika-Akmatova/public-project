git init                # Инициализация нового Git-репозитория
git clone <url>         # Клонирование репозитория с GitHub/GitLab
git remote add origin <url>  # Добавление удалённого репозитория

git status              # Проверка состояния репозитория
git add <file>          # Добавление файла в индекс (staging area)
git add .               # Добавление всех изменений
git reset <file>        # Удаление файла из индекса (но не из проекта)
git rm <file>           # Удаление файла из репозитория

git commit -m Сообщение  # Создание коммита
git commit --amend         # Изменение последнего коммита

git log                   # Просмотр истории коммитов
git log --oneline         # Краткая история коммитов
git log --graph --all --decorate --oneline  # Красивый граф
git diff                  # Разница между текущими изменениями и последним коммитом

git branch                # Список локальных веток
git branch -r             # Список удалённых веток
git branch <name>         # Создание новой ветки
git checkout <name>       # Переключение на ветку (устарело)
git switch <name>         # Переключение на ветку (современный вариант)
git switch -c <name>      # Создать и сразу переключиться
git merge <branch>        # Слияние ветки с текущей
git rebase <branch>       # Перемещение коммитов поверх другой ветки
git branch -d <name>      # Удаление локальной ветки
git push origin --delete <name>  # Удаление удалённой ветки

git fetch                 # Забрать изменения без их применения
git pull origin main      # Забрать и объединить изменения с GitHub
git push origin main      # Отправить коммиты в удалённый репозиторий

git merge --abort         # Отмена слияния, если есть конфликты
git rebase --abort        # Отмена ребейза
git checkout -- <file>    # Отменить изменения в файле
git reset --hard HEAD     # Отменить все изменения
git reset --hard origin/main  # Вернуть локальную ветку в состояние удалённой

git tag <tag_name>        # Создание тега
git tag -a <tag_name> -m Описание  # Аннотированный тег
git push origin <tag_name>  # Отправка тега в удалённый репозиторий
git tag -d <tag_name>     # Удаление локального тега
git push origin --delete <tag_name>  # Удаление удалённого тега

git tag <tag_name>        # Создание тега
git tag -a <tag_name> -m Описание  # Аннотированный тег
git push origin <tag_name>  # Отправка тега в удалённый репозиторий
git tag -d <tag_name>     # Удаление локального тега
git push origin --delete <tag_name>  # Удаление удалённого тега

git stash                 # Скрыть временные изменения
git stash pop             # Вернуть изменения из stash
git clean -f              # Удалить неотслеживаемые файлы
git reflog                # История всех действий в репозитории

Эта шпаргалка поможет вам быстро освоить Git!
Если что-то неясно — спрашивайте! 😊
