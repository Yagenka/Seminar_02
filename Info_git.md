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

  * Показать все фиксации: git log

  * Краткий формат предыдущей команды: git log --pret­­ty­=­short

  * Патчи: git log -p

  * Показать фиксации файла: git log file

  * Показать фиксации в директории: git log dir/

  * Состояния: git log --stat

  * Посмотреть автора изменений файла: git blame file

* Git - слияни­е/п­еребаза

* Git - обновл­ени­е/п­убл­икация

   команда | описание 
  --- | ---
   git log | показать все фиксации 
   git log --pret­­ty­=­short | краткий формат предыдущей команды
   git log -p | патчи
