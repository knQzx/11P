# **Репозиторий 11П класса**

Тут будет храниться код, написанный  классе или дома. У каждого ученика ест своя "ветка", в которой будет храниться его код. В ветке "main" будут храниться эталонные решения.

## Введение в Git

### Что такое Git?
Git — распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. Простыми словами, Git нужен для сохранения кода и при необходимости откатывания кода на предыдущие версии без использования Ctrl + Z.

### Частоиспользуемые Git-команды
```git add file.py``` - подготовить файл с названием file.py к сохранению. Чтобы не писать названия файлов по очереди, вместо file.py пишите '.'.

```git commit -m "comment"``` - добавить файлы в репозиторий с комментарием. Без комментария изменения сохранять нельзя!

```git status``` - проверить статус файлов(сохранены они или нет)

```git checkout name_of_branch``` - переключиться на другую ветку. 

```git stash``` - удалить несохранненый код(при условии, что вы ещё не писали git add) 

```git push``` - отправить сохраненные изменения в репозиторий

### Краткая инструкция как залить файлы в свою ветку
1. Выбор и переключение на свою ветку.
    - ![alt](https://i.ibb.co/BPFzNtn/Screenshot-2023-11-16-at-12-00-45.png)
2. 1-ый способ. Добавление файла в веб-версии.
      - ![alt](https://i.ibb.co/TrFK0bn/Screenshot-2023-11-16-at-11-05-20.png)
      - На данном этапе вы можете указать полный путь файла (не "main.py", а "/17/solutions/main.py")
      - ![alt](https://i.ibb.co/pJknZDY/Screenshot-2023-11-16-at-11-10-16.png)
      - Commit changes.
      - ![alt](https://i.ibb.co/qx6PSRJ/Screenshot-2023-11-16-at-11-11-21.png)
      - Успех.
3. 2-ый способ. Добавление файла из ПК.
      - ![alt](https://i.ibb.co/d6Dnzv0/Screenshot-2023-11-16-at-11-06-37.png)
      - Выбираем файл для добавления на своем ПК.
      - ![alt](https://i.ibb.co/s9KrFBS/Screenshot-2023-11-16-at-12-06-31.png)
      - Commit changes.
      - Успех.
