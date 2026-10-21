git@github.com:user_name/repository_name.git -- доступ по ssh
https://github.com/user_name/repository_name.git  -- доступ по https

Чтобы посмотреть все установленные настройки и узнать где именно они заданы, используйте команду:

```console
$ git config --list --show-origin
```
___________________________________________
Обязательные команды для работы
```console
$ git config --global user.name "John"
$ git config --global user.email johndoe@example.com
# обязательно указать имя и email с гитхаба
```
___________________________________________

git init - инициализация

git add  .    /   /example.examp --  добавление в отслеживание определенных файлов или всех файлов данной директории (.)

git rm ... -- убрать какие либо файлы

git rm --cached  --убрать файлы когда выше не сработало

git commit -m 'first commit' -- коммит всех отслеживаемых файлов, -m это сообщение, пояснение к изменению какого-то файлы

git remote add/remove origin 'ПУТЬ' - добавление/удаление ссылки на наш репозиторий, куда мы всё сохраняем

git push [-u] origin main -- пуш всех изменений, -m нужен при первом пуше с путем origin

git status -- посмотреть статус коммитов,

git log  --  логи коммитов