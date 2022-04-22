## Шпаргалка для Git

* Создать Git-ре­поз­иторий

  Из имеющейся директории | Из другого репози­тория 
  --- | ---
  cd proje­­ct_dir | git clone exist­­ing­­_dir new_dir
  git init | git clone git:/­­/gi­­th­u­b.c­­om/­­us­e­r­/r­­epo.git
  git add | git clone https­­://­­gi­t­h­ub.c­o­­m/u­­se­r­/­re­­po.git



* Git - локальный изменения

   задача | команда 
   ---- | ----
  Изменения в рабочей директории | git status
  Зафикс­иро­ванные файловые изменения | git diff
  Добавить изменённые файлы | git add file1 file2 file3


* Git - история

  * Показать все фиксации: git log

  * Краткий формат предыдущей команды: git log --pret­­ty­=­short

  * Патчи: git log -p

  * Показать фиксации файла: git log file

  * Показать фиксации в директории: git log dir/

  * Состояния: git log --stat

  * Посмотреть автора изменений файла: git blame file

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
