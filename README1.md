Настройка Git:
git config --global user.name "Your Name": Установка имени пользователя.
git config --global user.email "your_email@example.com": Установка email пользователя.
git config --global -l: Просмотр текущих настроек.
Создание репозитория:
git init: Инициализация нового репозитория.
Работа с файлами:
git status: Просмотр состояния рабочего каталога.
git add .: Добавление всех изменений в индекс.
git add filename: Добавление конкретного файла в индекс.
git reset: Очистка индекса.
Создание коммитов:
git commit -m "Your commit message": Фиксация изменений с комментарием.
Ветвление:
git branch: Просмотр списка веток.
git branch new_branch: Создание новой ветки.
git checkout branch_name: Переключение на другую ветку.
git checkout -b new_branch: Создание и переключение на новую ветку.
git merge branch_name: Слияние изменений из одной ветки в текущую.
Работа с удалёнными репозиториями:
git remote add origin remote_repository_url: Привязка локального репозитория к удаленному.
git push -u origin branch_name: Выгрузка ветки на удаленный репозиторий.
git pull: Загрузка изменений с удаленного репозитория.
Прочее:
git log: Просмотр истории коммитов.
git clone remote_repository_url: Клонирование удаленного репозитория.