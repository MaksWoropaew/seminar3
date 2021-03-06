# Инструкция по командам в Git

## Что такое Git и для чего он нужен?

С моей точки зрения это программа помшник любого программиста. С помощию Git можно делать проэкты быстрееи не боясь что можно что то упустить. Разделять задачу на более мелкие и понятные блоки, каждый блок прописывать можно отдельно.
Один человек может потом просто это все собрать в файл не погружаясь сильно в код, потому что все что нужно будет смотреть commit(коментарии к действиям,изменениям). Еще одно приемущество, что это все может работать дистанционно. 

## Для того чтобы начать работу нужно 

![скачать Git](https://git-scm.com)

![Download](download.png)

*Git нужно устанавливать после установки VC code*

**Сначала нужно создать папка и зайти в нее через VC code.**

## -Первым шагом нужно создать файл (file_name.md).

## -Вторым шагом инициализация этого файла по команде:

    git init

## -Третьим шагом добавляем его по команде:

    git add file_name

## -После измений в файле, что бы их сохранить нужно ввести следующие команды:

    git add
    git commit -m"comments"

## -Для показа изменений в файле нужно ввести команду:

    git diff (первые 7 символов лога комита)

## -Для отображения логов нужно ввести команду:

    git log

## -В одну линию(сокращенно):

    git log --oneline

## -В одну линию все коментарии с графиком(древом):

    git log --all --oneline --graph

## -Отображение изменений в файле(отображает файл в котором есть не записанные изменения):

    git status

## -Проверить изменения между логами:

    git checkout log_name(первые 6-7 цифр)

# Больше команд про древо

## -Просмотр древа:

    git branch

## -Создание нового древа(параллельного):

    git branch branch_name

## -Перемещение между древом:

    git checkout branch_name

## -Удаление ветки древа:

    git branch -d branch_name

## -Слияние веток
**Нужно обязательно быть в той ветке куда идет слияние!**

    git merge branch_name(откуда идет слияние)

*Если слияние происходит с ошибкой, VS code предложит несколько вариантов слияния*

![skrin](skrin.png)

**Пример: git merge branch_2**
* _Оставить не измения главную ветвь(branch_1)_
* _Заменить главную ветвь, с чем есть конфликт(несоответсвие)(branch_2)_
* _Внести обе ветки по порядку и возможностью отредактировать и сохранить как будет убодней(branch_1+branch_2)_
* _Оставить без изменений_


*Продолжение следует...*

## Работа с Git hub
