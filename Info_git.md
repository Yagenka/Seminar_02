## Шпаргалка для Git

* Создать Git-ре­поз­иторий

   * Из имеющейся директории
cd proje­­ct_dir
git init
git add .

   * Из другого репози­тория
git clone exist­­ing­­_dir new_dir
git clone git:/­­/gi­­th­u­b.c­­om/­­us­e­r­/r­­epo.git
git clone https­­://­­gi­t­h­ub.c­o­­m/u­­se­r­/­re­­po.git

* Git - локальный изменения

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
