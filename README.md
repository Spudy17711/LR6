# LR6
Лабораторная работа №6
Репозиторий клонирован на компьютер
![screen1](https://github.com/Spudy17711/LR6/blob/master/screenshots/1.jpg)

Добавлен файл и подтянуты изменения в локальный 
![screen2](https://github.com/Spudy17711/LR6/blob/master/screenshots/1,5.jpg)

Получена история операций для каждой ветки
![screen3](https://github.com/Spudy17711/LR6/blob/master/screenshots/2.jpg)

Получена последние изменения
![screen4](https://github.com/Spudy17711/LR6/blob/master/screenshots/3.jpg)

Выполнено слияние в ветку master 
![screen5](https://github.com/Spudy17711/LR6/blob/master/screenshots/4.jpg)
![screen6](https://github.com/Spudy17711/LR6/blob/master/screenshots/4,5.jpg)

Внесено изменение и после закоммичено
![screen7](https://github.com/Spudy17711/LR6/blob/master/screenshots/5.jpg)

Осуществлен "хард" откат коммита
![screen8](https://github.com/Spudy17711/LR6/blob/master/screenshots/6.jpg)

Создана ветка для отчета report и загружаем в удаленный репозиторий
![screen9](https://github.com/Spudy17711/LR6/blob/master/screenshots/7.jpg)

Лог команд
```
git clone https://github.com/Spudy17711/LR6
git pull
git reflog --all
git log -p
git checkout master
git merge master
git status
git add addfile.txt
git commit -m "addition"
git reset --hard @
git checkout -b report
git push --set-upstream origin report
```
