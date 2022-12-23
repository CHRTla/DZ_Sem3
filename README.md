# Конспект от Дроздова Савелия

## методы git, которые я знаю и описание к ним

1. init - инициализация гита

2. add "имя_файла.разширение" или вписать ".", чтобы добавить всё - добавление к сохранению

3. commit -m "краткое_описание" - сохранение версии 

4. reset --hard "sha код коммита"/HEAD~1(для удаления главного коммита) - удаление коммитов

5. branch - выводит имена веток

    * branch "имя_ветки" - создаёт новую ветку с именем "имя_ветки"
    
    * branch -d "имя_ветки" - удаляет ветку с именем "имя_ветки"

    * branch -M "имя_ветки" - создаёт основную ветку для удалённого репозитория

6. diff - разница межу коммитами 

7. log - история изменений
    * log --graph - история изменений с графом

8. status - статус файлов в репозитории

9. clone "ссылка_на_удалённый_репозиторий" - копирует удалённый репозиторий

10. remote add origin "ссылка"- связывает git с удалённым репозиторием

11. pull - заполучить новейшие изменения с удалённого сервера

12. push - отправить изменения на удалённый сервер
    * push -u origin "имя_ветки" отправить изменёную ветку

Домашнее Задание: 

> # Инструкция для работы с MD
>
>## Выдиление списка
>
>*курсив* - * текст * или _ txt _ (без пробелов)
>
>**полужирный** - ** текст ** или __ txt __ (без пробелов)
>
>совмещение: **_txt_** - _ ** текст ** _ (без пробелов)
>
>## Списки
>
>ненумерованные списки (со звёздочкой или + в начале):
>* item 1
>* item 2
>* item n
>+ item n+1
>
>нумерованные списки (с цифрами):
>1. пункт1
>2. пункт2
>
>## Работа с изображениями
>вставка изображения:
>![фенек (бежит)](https://animalreader.ru/wp-content/uploads/2014/04/fenek5-e1398185616705.jpg)
>
>[1]: https://animalreader.ru/wp-content/uploads/2014/04/fenek5-e1398185616705.jpg "фенек"
>
>## Ссылки
>*<code>
[фенек][1]
</code>
>
>## Работа с  таблицами
>
><code>Item      | Value | Quantity
:-------- |:-----:| -------:
Computer  | 1600  | 3
Phone     | 12    | 2
Pipe      | 1     | 1</code>
>
>## Цитаты
>
><code>
>
>> Это просто цитата 
>>> А это уже вложенная цитата
></code>
>
>## Заключение
>
>На этом курсе я узнал и изучил markdown и git.