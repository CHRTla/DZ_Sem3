## 2 Семинар
*git help - показывает все команды и значения*
## Теперь установим email. Принцип тот же.
- git config --global user.email "<адрес_почты@email.com>"
*** git config --global user.name "<ваше_имя>" ***
~~git init - ~~ инициализация  локального репозитория
<git add .- добавление файла

git commit -m "5st commit" - добавляем коммит
***git version -*** версия git
git log - информация о всех коммитах
git checkout master - возврат к главному файлу (текущей версии)
git checkout ... - переход к нужному коммиту
git diff - разница между сохраненным файлом и закоммиченным файлом
__Создание веток__
git branch - посмотреть созданные ветки
git branch name - переход в ветку name
__Слияние веток__
git merge creating - слияние ветки master с указанной веткой (creating)
git log --graph - визуализация веток
Создали вторую ветку
__Конфликты при слиянии__
Конфликты возникают когда коммиты затрагивают общее рабочее пространство
__Клонирование репозитория__
git clone
__Добавление папки__
git remote add origin master
