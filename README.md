# less-boilerplate
Gulp less boilerplate

# Установка

Установить Git + Git Bash
https://git-scm.com/downloads

Установить Nodejs
https://nodejs.org/download/


Запустить Git Bash и выполнить команды:
```
cd папка_с_проектом
npm i -g gulp rimraf
npm i
gulp assets
```

# Разработка

Использовать такие команды:

Для перемещения по директориям:
```
cd путь_к_директории
```

Для компиляции всего:
```
gulp assets
```

Для запуска watch (который будет следить за изменениями и автоматически перекомпилировать все):
```
gulp watch
```

Для удаления директории (которая не удаляется виндой):
```
rimraf путь_к_папке
```
