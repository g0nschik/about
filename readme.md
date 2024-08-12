# Шпаргалка по GIT

---

* Система контроля версий, или VCS (SCM), — программа, позволяющая контролировать изменения в проекте.
* Git — один из примеров системы контроля версий: он позволяет хранить, изменять и анализировать историю проекта.
* Git — незаменимый в команде инструмент, ведь он помогает объединять результаты работы нескольких человек.

---

##### Инициализция

* Инициализировать репозиторий можно с помощью команды _git init_
* Проверить статус, или состояние, репозитория поможет команда _git status_
* Если вы ошиблись и случайно инициализировали не ту папку, можно «разгитить» её — удалить скрытую подпапку _.git_

```
git init
```

_Добавление файлов_

```
git add *
```

_Коммит_

```
git commit -m "Комментарий"
```