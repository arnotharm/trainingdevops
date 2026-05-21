# Контроль версий или GIT / GitHub

#### Этапы старта проекта:
-	Создать репозиторий в Git Hub
- В директории проекта создаем локальный репозиторий - **git init** (создается ".git")
- Добавляем нужные файлы или все в INDEX - **git add .** или **git add index.html**
>![](https://bramus.github.io/ws2-sws-course-materials/assets/xx/git-remote.png)

- Создание первого коммита - **git commit -m "Первый коммит"**
- Подключение к удаленному репозиторию - **git remote add origin** **https://github.com/логин/репозиторий.git**
- Отправля на github репозитороий - **git push origin main** (в зависимости от ветки , в нашем случаи это "main")
#### Работа в команде - нужные команды **git**
* **``` git branch -a```** (показывает все ветки которые есть на проекте)
* **``` git checkout название_ветки```** (переключаемся на нужную ветку и работаем там)
* **``` git pull origin название_ветки```** (синхранизируем все последние актуальные изменения)
* > [Git: курс на YouTube](https://www.youtube.com/playlist?list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb)