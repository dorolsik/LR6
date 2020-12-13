# LR6
Генрихов Василий 4916 Лабораторная работо 6

На сайте GitHub сделал копию https://github.com/Kurtyanik/LR6/

![Копированный репозиторий](скрип/s1.png)

С помощью команды _cd laba6_ в консоли Git Bash перешёл в созданную папку laba6

Использовал команду _git init_ чтобы инициализировать гит в данной папке

![](скрип/s2.png)

Командой _git cjnfing --global user.name/email_ внес свои данные.

![](скрип/s3.png)

Командой _git remote add origin_ связал папку с удалённым репозиторием на сайте GitHub

![](скрип/s4.png)

Затем через графический интерфейс GitHub добавил новый файл _file.txt_ в удалённый репозиторий в ветку __master__

![](скрип/s21.png)

![](скрип/s22.png)

![](скрип/s20.png)

Пользуясь командой _git pull origin master_ загрузил изменения из удалённого репозитория в локальный

![Git pull](screenshots/Screenshot_9.png)

Командой _git log_ получил список операций/коммитов

![git log](screenshots/Screenshot_10.png)

Используя _git show *commit SHA-1*_ получил более подробную информацию по последнему изменению

![git show](screenshots/Screenshot_11.png)

Командой _git checkout -t branch1_ переключился на другую ветку **branch1**

![git checkout](screenshots/Screenshot_12.png)

Попытался выполнить слияние веток **master** и **branch1** командой _git merge branch1_ и получил ошибку

![Merge error](screenshots/Screenshot_13.png)

Вручную изменил файл mergefile.txt, вызвавший ошибку слияния и выполнил коммит

![Fix](screenshots/Screenshot_14.png)

Выполнил слияние веток **master** и **branch1** а затем удалил ветку **branch1** командой _it

![Merge](screenshots/Screenshot_15.png)

![Branch delete](screenshots/Screenshot_16.png)

Запушил всё в удалённый репозиторий командой _git push origin master_ (Строка logon failed вылезает из-за какой-то внутренней ошибки)

![Push1] (скриншоты / Screenshot_17.формат PNG)

Затем сделал несколько изменений, добавив новые файлы

![Новые файлы] (скриншоты / Screenshot_19.формат PNG)

![Новые файлы git] (скриншоты / Screenshot_20.формат PNG)

Командой _git reset --hard HEAD~1_ выполнил откат последнего коммита - добавления файла **Новый текстовый документ.формат txt**

![Жесткий сброс] (скриншоты / Screenshot_22.формат PNG)

Запушил изменённую ветку

![Push2] (скриншоты / Screenshot_23.формат PNG)

![РезультатPush2] (скриншоты / Screenshot_24.формат PNG)

Пользуясь командой _git checkout -b otchet_ создал новую ветку **otchet**

![Новая ветвь] (скриншоты / Screenshot_25.формат PNG)


Текущая история _git log --graph_ . Аргумент --graph позволяет графически изобразить ветки и коммиты на них

![Git log2](скриншоты/Screenshot_26.формат PNG)

С помощью команды _git add ._ подготовил все новые файлы в папке **lab6** к пушу

![Мерзавец добавляет .] (скриншоты/Screenshot_28.формат PNG)

Запушил файлы скриншотов в удалённый репозиторий

![Git add .](screenshots/Screenshot_29.png)

Оформляю отчёт в файле **README.md** используя блокнот

![Readme](screenshots/Screenshot_31.png)



Лог команд из папки **.git / журналы**

![Журналы] (скриншоты / Screenshot_30.формат PNG)

Финальный результат команды _git log_

![Git log3] (скриншоты / Screenshot_32.формат PNG)

Все файлы скриншотов лежат в папке **screenshots**
