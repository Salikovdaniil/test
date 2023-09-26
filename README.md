# Словарь Git
Я, сегодня завтра и вчера
## Создание репозитория 

...
git init
...
## Создание репозитория на локальном компьютере

## Создать на компьютере папку Git
## В папке создать несколько файлов. Например, index.txt
## В файл внести изменения.
## Открыть git bash
## Залогиниться - В git Bash набрать команды
git config --global user.name "" 
git config --global user.email ""
## Посмотреть в какой папке мы находимся
pwd
## Указать путь в папку Git
cd ‘путь к папке’
## Создать из текущей папки GIT локальный репозиторий
git init
## Добавить файлы из репозитория в индекс
git add .
## Сохранить текущую версию
git commit -m "Первый коммит"
## В GitHub создать репозиторий с именем GitName
## В Git Bash набрать команду
git remote add origin https://github.com/ВашЛогинНаГитхаб/GitName.git
## Создать основную ветку
git branch -M main
## Перенести локальный репозиторий
git push -u origin main
## Продолжим работать с .gitignore:
touch .gitignore
# Добавляем в файл правила игнорирования по примеру выше
git add .gitignore
git commit -m 'update gitignore'
