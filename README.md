# Команды Git
## Создание репозитория на локальном компьютере
```
git config --global user.name ""
```
```
git config --global user.email ""
```
>залогиниться
```
pwd
```
>показывает текущую папку
```
ls -la
```
>покзывает содержимое папки
```
cd 'FolderPath'
```
>указывает путь к папке
```
git init
```
>создает репозиторий из текущей папки
## Запись изменений в репозиторий
```
git add .
```
>добавляет файлы из репозитория в индекс
```
git commit -m "commit`"
```
>сохраняет текущие изменения
```
git status
```
>показывает состояние репозитория
```
git log
```
>показывает историю коммитов
```
git remote add origin https://github.com/ВашЛогинНаГитхаб/GitName.git
```
>подключает к локальному репозиторию удаленный
```
git branch -M main
```
>создает основную ветку
```
git push -u origin main
```
>переносит локальный репозиторий
```
 git remote -v
```
>чтобы посмотреть какой удаленный репозиторий подключен
```
git branch new_branch_name
```
>создание новой ветки
```
git checkout -b new_branch_name
```
>автоматический переход в ветку
```
git branch
```
>просмотр списка веток
```
git branch -d existing_branch_name
```
>удаление ветки
```
git merge existing_branch_name
```
>слияние двух веток
