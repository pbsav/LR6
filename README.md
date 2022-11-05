# LR6
Лабораторная работа №6

## Цель работы 

Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## Ход работы

1. Создал аккаунт на сайте GitHub - pbsav.
2. Сделал копию в личное хранилище.
![(рис 1)](./screenshots/1.jpg)
3. Установил Git.
4. После установки настроил клиент git, введя имя пользователя (Группа
Фамилия И.О.) и email.
![(рис 2)](./screenshots/2.jpg)
5. Клонировал свой личный удалённый репозиторий на компьютер.
![(рис 3)](./screenshots/3.jpg)
6. Добавил файл через интерфейс GitHub. Подтянуть изменения в
локальный репозиторий.
![(рис 4)](./screenshots/4.jpg)
Работу продолжил локально.
7. Получил историю операций для каждой из веток.
![(рис 5)](./screenshots/5.jpg)
![(рис 6)](./screenshots/6.jpg)
8. Просмотрел последние изменения.
![(рис 7)](./screenshots/7.jpg)
9. Выполнил слияние в ветку master, разрешив конфликт.
![(рис 8)](./screenshots/8.jpg)
![(рис 9)](./screenshots/9.jpg)
10. Удалил побочную ветку после успешного слияния.
![(рис 10)](./screenshots/10.jpg)
11. Сделал изменения и зафиксировал их.
![(рис 11)](./screenshots/11.jpg)
12. Сделал откат коммита.
![(рис 12)](./screenshots/12.jpg)
13. Создал ветку для отчёта.
![(рис 13)][./screenshots/13.jpg]

## Лог команд 

   83  git clone https://github.com/pbsav/LR6.git
   84  cd LR6
   85  git fetch origin
   86  git checkout branch1
   87  git checkout patch1
   88  git checkout patch1
   89  git log
   90  git checkout master
   91  git log master
   92  git reflog
   93  git merge patch1
   94  git branch -a patch1
   95  git branch -d patch1
   96  git puch origin -d patch1
   97  git push origin -d patch1
   98  git push origin -d patch1
   99  git add ripfile.txt
  100  touch ripfile.txt
  101  git add ripfile.txt
  102  git commit -m "its cool!"
  103  git log --graph
  104  git reset --hard ~HEAD
  105  git reset --hard HEAD~
  106  git log --graph
  107  git branch myreport
  108  git checkout myreport
  109  git push https://github.com/pbsav/LR6.git


## Вывод

Я изучил базовые возможности системы управления версиями, получил опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.