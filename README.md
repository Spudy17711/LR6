# LR6
Лабораторная работа №6
__1.Репозиторий клонирован на компьютер__
![screen1](https://github.com/Spudy17711/LR6/blob/master/screenshots/1.jpg)

__2.Добавлен файл и подтянуты изменения в локальный__
![screen2](https://github.com/Spudy17711/LR6/blob/master/screenshots/1,5.jpg)

__3.Получена история операций для каждой ветки__
![screen3](https://github.com/Spudy17711/LR6/blob/master/screenshots/2.jpg)

__4.Получена последние изменения__
![screen4](https://github.com/Spudy17711/LR6/blob/master/screenshots/3.jpg)

__5.Выполнено слияние в ветку master__ 
![screen5](https://github.com/Spudy17711/LR6/blob/master/screenshots/4.jpg)
![screen6](https://github.com/Spudy17711/LR6/blob/master/screenshots/4,5.jpg)

__6.Внесено изменение и после закоммичено__
![screen7](https://github.com/Spudy17711/LR6/blob/master/screenshots/5.jpg)

__7.Осуществлен "хард" откат коммита__
![screen8](https://github.com/Spudy17711/LR6/blob/master/screenshots/6.jpg)

__8.Создана ветка для отчета report и загружаем в удаленный репозиторий__
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
