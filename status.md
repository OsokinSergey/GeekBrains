# Наименование
`git status` -  получение информации от git о его текущем состоянии.
# Обзор
`git status` [<options…​>] [--] [ <pathspec…>​]
# Описание
Отображает пути, имеющие различия между текущим состоянием и текущим коммитом HEAD, пути, имеющие различия между рабочим деревом и индексным файлом, и пути в рабочем дереве, которые не отслеживаются Git'ом (и не игнорируются gitignore[5]). Первое - это то, что вы зафиксируете, выполнив git commit; второе и третье - то, что вы можете зафиксировать, выполнив git add перед git commit.