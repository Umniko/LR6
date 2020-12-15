# LR6
## Лабораторная работа №6
### Выполнил студент группы 4916 Алексей Шихотов
### Ход работы:

На сайте GitHub выполнил форк https://github.com/Kurtyanik/LR6/
![](1.png)
Далее я произвёл установку в config имя пользователя и его почту.
Однако в следствии последующих ошибок в программном обеспечении компьютера данные изменения не были зафиксированы.
Также, мне пришлось перейти в Git Bash для дальнейшего выполнения лабораторной работы.
![](2.png)
После я перешёл в созданную мной папку и использовал команду git init чтобы инициализировать гит в данной папке.
![](3.png)
Командой git remote add origin связал папку с удалённым репозиторием на сайте GitHub
![](4.png)
С помощью команды git clone клонировал проект в свою папку.
![](5.png)
Далее я создал новый файл и закоммитил его в master. Поскольку я не вводил комментарий и описание, то GitHub их создал автоматически.
![](6.png)
![](7.png)
![](8.png)
Затем я подтянул изменения в локальный master и с помощью команды git log получил список операций.
![](9.png)
![](10.png)
После я помощью команды git show открыл подробности последнего коммита.
![](11.png)
Далее я переключился на ветку branch1 и попытался выполнить слияние.
![](12.png)
Однако не получилось из-за конфликта в файле.
![](13.png)
Вручную открыв и справив конфликт, я исправил ошибку.
Затем я подготовил файл к коммиту по средством команды git add и закоммитил его. После повторил операцию.
![](14.png)
После я заканчиваю слияние веток.
![](15.png)
Следующим шагом было удаление ветки branch1.
![](16.png)
Затем я запушил все изменения в удалённый master.
![](17.png)
Далее я добавил несколько изменений в удалённый мастер по средством добавления нескольких файлов.
![](18.png)
И затем подгрузил изменения в локальный мастер.
![](19.png)
После выполнил git log для показа последний коммитов.
![](20.png)
А затем я выполнил откат к предыдущему коммиту с помощью команды git reset --hard HEAD~1.
Ниже HEAD указывает на текущий коммит.
![](21.png)
Далее запушил обновлённую ветку.
![](22.png)
Затем я приступил к созданию новой ветки для отчёта. Выполнив команду git checkout -b я создал ветку otchet.
![](23.png)
После я подтянул в ветку изменения из удалённого master и выполнил git log --graph для визуализации веток и коммитов в виде графов.
![](24.png)
Далее я выболнил подготовку к коммиту скриншоты и создал коммит.
![](25.png)
После чего запушил изменения в удалённый otchet.
![](26.png)
Финальный скрин списка операций.
![](27.png)
Отчёт оформлен в файле README.md
![](28.png)