##ОТЧЁТ О ЛАБОРАТОРНОЙ РАБОТЕ №6 

## ПО ОСНОВАМ ПРОГРАММИРОВАНИЯ



###Ход работы:

На сайте GitHub сделал копию https://github.com/Kurtyanik/LR6/

![Копированный репозиторий](scr/0.png)

С помощью команды _cd Desktop/lab6_ в консоли Git Bash перешла в созданную на рабочем столе папку lab6

Использовал команду _git init_ чтобы инициализировать гит в данной папке

Командой _git remote add origin_ связала папку с удалённым репозиторием на сайте GitHub

![Git init](scr/1.png)

![Git remote add origin](scr/2.png)

Затем через графический интерфейс GitHub добавил новый файл _Index.html_ в удалённый репозиторий и добавила его в ветку __master__

![Новый файл](scr/док.png)

Пользуясь командой _git pull origin master_ загрузила изменения из удалённого репозитория в локальный

![Git pull](scr/3.png)

Командой _git log_ получила список операций/коммитов

![git log](scr/4.png)

Используя _git show *commit SHA-1*_ получила более подробную информацию по последнему изменению

![git show](scr/5.png)

Командой _git checkout -t branch1_ переключилась на другую ветку **branch1**

![git checkout](scr/6.png)

![git checkout](scr/8.png)

![git checkout](scr/9.png)

Попыталась выполнить слияние веток **master** и **branch1** командой _git merge branch1_ и получила ошибку

![Merge error](scr/10.png)

Вручную изменила файл mergefile.txt, вызвавший ошибку слияния и выполнил коммит

![Fix](scr/11.png)

Выполнила слияние веток **master** и **branch1** а затем удалил ветку **branch1** командой _git branch -d branch1_

![Merge](scr/13.png)

![Branch delete](scr/14.png)

Запушила всё в удалённый репозиторий командой _git push origin master_ (Строка logon failed вылезает из-за какой-то внутренней ошибки)

![Push1](scr/15.png)

Затем сделала несколько изменений, добавив новые файлы

![New files](scr/16.png)

![New files git](scr/17.png)

Командой _git reset --hard HEAD~1_ выполнила откат последнего коммита - добавления файла **Новый текстовый документ.txt**

![Hard reset](scr/18.png)

Запушила изменённую ветку

![Push2](scr/19.png)

![Push2 result](scr/20.png)

Пользуясь командой _git checkout -b otchet_ создала новую ветку **otchet**

![New branch](scr/22.png)

Текущая история _git log --graph_ . Аргумент --graph позволяет графически изобразить ветки и коммиты на них

![Git log2](scr/23.png)

С помощью команды _git add ._ подготовила все новые файлы в папке **lab6** к пушу

![Git add .](scr/24.png)

Запушила файлы скриншотов в удалённый репозиторий

![Git add .](scr/25.png)

Оформила отчёт в файле **README.md** используя блокнот

![Readme](scr/26.png)


Лог команд из папки **.git/logs**

![Logs](scr/27.png)

Финальный результат команды _git log_

![Git log3](scr/28.png)

Все файлы скриншотов лежат в папке **scr**
