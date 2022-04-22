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

Слияние ветку в текущую
git merge branch
Переба­зир­овать в ветку
gir rebase branch
git rebase master branch
Отменить переба­зир­ование
git rebase --abort
Инструмент слияния для разрешения конфликтов
git mergetool
Конфликты против файла базы
git diff --base file
Diff изменений, сделанных другими людьми
git diff --theirs file
Diff ваших действий
git diff --ours file
После решения конфликтов
git rebase --continue

* Git - обновл­ени­е/п­убл­икация

   команда | описание 
  --- | ---
   git log | показать все фиксации 
   git log --pret­­ty­=­short | краткий формат предыдущей команды
   git log -p | патчи
