> git init – инициализация локального репозитория

> git status – получить информацию от git о его текущем состоянии

> git add – добавить файл или файлы к следующему коммиту

<!---
Домашнее задание к семинару 
"Урок 3. Работа с удалёнными репозиториями"
Выполнил Павел Овчинников
-->

> # Работа с удаленным репозиторием. Команды: clone, fetch, push, pull.

> git clone - Клонирование существующего репозитория.При выполнении git clone с сервера забирается (pulled) каждая версия каждого файла из истории проекта. 


usage: git clone [<"options">] [--] <"repo"> [<"dir">]


> git fetch - связывается с удалённым репозиторием и забирает из него все изменения, которых у вас пока нет и сохраняет их локально.

> git pull - работает как комбинация команд git fetch и git merge, т. е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.

> git push - используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий.