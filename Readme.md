#  инструкция для работы с Git  и удаленными репозиториями


## Что такое Git?
Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий 


## Подготовка репозитория
Для создания репозитория необходимо выполнить команду *git init* в папке  с репозиторием и у вас создаться  репозиторий (появится скрытая папка git)

## Создание коммитов
Для того чтобы создать коммит необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m"сообщение к коммиту"*.Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***

### Git add
Для добавления  изменений и коммит используется  команда *git add*. Чтобы использовать команду *git add*  напишите *git add <имя файла>*

## Перемещение между  сохранениями
Для того, чтобы перемещаться между коммитами, исползуется команда  *git checkout*.Используется она в папке с репозиторием следующим образом: git checkout <номер коммита>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть  состояние  репозитория  используется команда *git status*. Для этого  необходимо в папке с репозиторием  написать *git status*   и вы увидите были ли  изменения в файлах, или их не было

### Журнал изменений
Что бы внести изменения мы используем команду 

## Ветки в Git
В гите можно создавать несколько веток

### Создание ветки
Для того чтобы создать ветку используется команда "git branch". Делается это 
следующим образом - в папке  с репозиторием : *git branch <название новой ветки>*

## Слияние веток
Для того чтобы добавитьветку в текущую ветку исполльзуется команда *git merge <name branch>*

# Инструкция для работы с Макдауном

## Работа с изображениями
Чтобы вставить изображения в текст достаточно  написать следующее:![Привет post!](post_5c606e629f934.jpg) 

## Выделение текста
чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания(_). Например *вот так* или  _вот так_
Чтобы выделить текст полужирным необходимо обрамить его двойными звездочками или двойным знаком нижнего подчеркивания(__). Например **вот так** или __вот так__

альтернативные  способы  выделения текста  жирным или курсивом нужны для того, чтобы мы могли совмещать  оба  этих способа. Например, _текст может быть выделен  курсивом и при этом быть **полужирным_.

## Ссылки

### Конец ДЗ
# Переключаемся в master
git checkout master
# Обновляем локальную ветку с сервера
git pull origin master

# Делаем merge вашей ветки, в ветку в которой вы находитесь

## Как можно создать репозиторий

Если мы находимся в папке (!) и хотим сделать из нее репозиторий, то вызываем команду «git init», и эта папка становится репозиторием.

Если мы хотим клонировать репозиторий из GitHub на свой ПК, то мы пользуемся командой «git clone». При этом обратите внимание: не нужно пользоваться командой «git init», команда clone не только скачивает файлы из интернета, но и инициализирует репозиторий в скачанной папке. На самом деле она делает сильно больше, но нам важно, что в скачанной папке у нас уже будет репозиторий и никак дополнительно инициализировать его не надо.

## Пункт 4. Внимательно следим за тем, из какой папки вы вызываете команды

Терминал всегда показывает, в какой папке вы сейчас находитесь, но первое время студенты чаще смотрят на то, какая папка открыта в визуальном интерфейсе VSCode, а не на то, что написано в терминале. Обращайте, пожалуйста, внимание на название папки, которая указана в приглашении к вводу команд терминала. До тех пор, пока вы не привыкнете к работе с терминалом, внимательно следите за тем, что вы создаете репозитории только во вновь созданных для урока папках. Не нужно создавать репозитории из рабочего стола или других больших папок.


## Пункт 5. Не нужно создавать репозитории внутри другого репозитория

Повторюсь: не нужно создавать репозиторий внутри репозитория. Прежде чем вызывать команды «git init» или «git clone», сначала убедитесь, что вы точно не внутри репозитория. Вызовите «git status» и убедитесь, что вы находитесь в папке, а не в репозитории. Если «git status» выдал ошибку «fatal: not a git repository (or any of the parent directories): .git», значит, вы в этой папке можете воспользоваться одним из способов создания репозитория, рассмотренным выше и на лекциях. Либо «git init», либо «git clone», но не обоими одновременно. 

Важно! Иногда студенты сначала вызывают «git init» и потом «git clone». Но тем самым вы нарушаете правило не создавать репозиторий внутри репозитория. Обращайте на это внимание.

## Продолжение
  


