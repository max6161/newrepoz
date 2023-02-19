readme.md
# Инструкция для работы с Git и удалёным репозиториями

## Git ?
Это одна из реализаций распределённых систем
контроля версий, имеющая как и локальные, так
удалённые репозитории. Является самой популярным
реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду
"git init"
в папке с репозиторием и у Вас создаться
репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда
*git add*. Чтобы использовать команду "git add" напишите
*git add "<имя файла>"

### Просмотр состояния репозитория

Для того, чтобы посмотреть состояние репозитория
используется команда "git status". Для этого необходимо
в папке с репозиторием написать "git status", и Вы
увидите были ли измения в файлах, или их не было.

### Создание коммитов git commit
Для того, чтобы создать коммит (сохранение) необходимо
выполнить команду *git commit*. 
(Команда git commitберет все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, затем добавляет ориентировочные ориентировки на этот слепок.)

### проверка состояния файлов git status
Для этого нужно ввести команду *git status* показывает состояние файлов в рабочем каталоге и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидаются комиссии в индексе

### git diff 
представляет собой многоцелевую команду Git, которая инициирует функцию сравнения источников данных Git — коммитов, веток, файлов и т. д

### git difftool
Команда git difftool просто запускает внешнюю утилиту сравнения для показа различий в двух деревьях, на случай если вы хотите использовать что-либо отличное от встроенного просмотрщика git diff.

### git reset 
Команда git reset, как можно догадаться из названия, используется в основном для отмены изменений. Она изменяет указатель HEAD и, опционально, состояние индекса. Также эта команда может изменить файлы в рабочем каталоге при использовании параметра --hard, что может привести к потере наработок при неправильном использовании, так что убедитесь в серьёзности своих намерений прежде чем использовать его.

### git rm
Команда git rm используется в Git для удаления файлов из индекса и рабочей копии. Она похожа на git add с тем лишь исключением, что она удаляет, а не добавляет файлы для следующего коммита.

### git mv
Команда git mv — это всего лишь удобный способ переместить файл, а затем выполнить git add для нового файла и git rm для старого.

### git clean
Команда git clean используется для удаления мусора из рабочего каталога. Это могут быть результаты сборки проекта или файлы конфликтов слияний.
1
Команда git clean используется для удаления мусора из рабочего каталога. Это могут быть результаты сборки проекта или файлы конфликтов слияний. 


### git clone 
П
### Git Merge
Слияние — обычная практика для разработчиков, использующих системы контроля версий. Независимо от того, созданы ли ветки для тестирования, исправления ошибок или по другим причинам, слияние фиксирует изменения в другом месте. Слияние принимает содержимое ветки источника и объединяет их с целевой веткой. В этом процессе изменяется только целевая ветка. История исходных веток остается неизменной.

