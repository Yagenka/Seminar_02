## Шпаргалка для Git

* Создать Git-ре­поз­иторий

Из имеющейся директории | Из другого репози­тория 
  --- | ---
  cd proje­­ct_dir | git clone exist­­ing­­_dir new_dir
git init | git clone git:/­­/gi­­th­u­b.c­­om/­­us­e­r­/r­­epo.git
git add | git clone https­­://­­gi­t­h­ub.c­o­­m/u­­se­r­/­re­­po.git



* Git - локальный изменения

Изменения в рабочей директории
git status
Зафикс­иро­ванные файловые изменения
git diff
Добавить изменённые файлы
git add file1 file2 file3
Удалить файл
git rm file
git rm dir/ -r
(рекур­сивно внутри директ­ории)
Посмотреть файлы, готовые к фиксации
git diff --cached
Фиксация изменений
git commit
git commit -m "My messag­­e"
git commit -a -m "My Messag­­e"
(только зафикс­иро­ванные файлы, автома­тич­еское добавл­ение)
Изменение последней фиксации
git commit --amend
Вернуть изменения в файл
git checkout -- file
Вернуть изменения (новая фиксация)
git revert HEAD
Вернуться к зафикс­иро­ванному состоянию
git reset --hard HEAD

* Git - история

* Git - слияни­е/п­еребаза

    команда | описание 
     --- | ---
  git merge branch | cлияние ветку в текущую
  git rebase branch, git rebase master branch | переба­зир­овать в ветку
  git rebase --abort | отменить переба­зир­ование
  

* Git - обновл­ени­е/п­убл­икация

   команда | описание 
  --- | ---
   git log | показать все фиксации 
   git log --pret­­ty­=­short | краткий формат предыдущей команды
   git log -p | патчи
