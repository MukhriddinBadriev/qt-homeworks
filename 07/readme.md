# Домашнее задание к занятию "Рисование графиков"

### Цель задания

В результате выполнения этого задания вы научитесь строить линейные графики при помощи QtCharts (можно QCustomPlot)

------

### Инструкция к заданию

1. Скачать проект с прекодом.
2. Добавить в CmakeList.txt модуль для работы с QtCharts
* Если выполняете при помощи QCustomPlot то соответственно добавить библиотеки(можно взять из примеров лекций) и добавить модуль необходимый для работы QCustomPlot
4. Выполнить требования задания.

------

### Задание 1. 

1. Необходимо отобразить первую секунду обработанных данных.
2. Наполнение серии данными необходимо реализовать внутри лямбда-функции findMax.
3. Поместить сигнал внутрь findMax сигнализирующий о готовности данных для отрисовки.
4. Отображение графика должно быть реализовано в созданном вами слоте в MainWindow.
5. График должен отображаться в новом окне.

------

###### Дополнительные сведенья

1. Частота дискретизации данных составляет 1000 Гц.

### Правила приема работы

1. Отправлена ссылка на репозиторий с кодом ДЗ

------

### Критерий зачета

* Программа работает стабильно.
* При обновлении данных график также обновляется.
