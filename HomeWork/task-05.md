![Logo](https://github.com/Anton-Pronkin/net-courses-external/raw/master/HomeWork/media/epam_logo.png)


# Наследование

##  Рекомендации к выполнению

1.  Создать решение в папке ‘05-inheritance’.
2.  Название решения (solution) – ‘Inheritance’.
3.  Для каждого задания должен быть отдельный проект в составе решения.
4.  Название проекта – Task\#, например, Task1, Task2, Task3 и т.д.
5.  Целевой рантайм - .NET Core 3.1.

## Задание 1

### Основное

На основе класса User (см. задание 1 из предыдущей темы), создать класс Employee, описывающий сотрудника фирмы. В дополнение к полям пользователя добавить свойства Experience (стаж работы) и Title (должность). Обеспечить нахождение класса в заведомо корректном состоянии. Подумать над новыми свойствами с точки зрения использования этого класса в будущем.

### Требования

1.  Класс Employee должен быть унаследован от базового класса User.
2.  Свойство Experience должно быть вычисляемым на основе даты поступления на работу.
3.  Обеспечить нахождение класса в заведомо корректном состоянии.
4.  Продемонстрировать использование класса в консольном приложении.
5.  Продемонстрировать обработку сценариев с попытками создать объект класса Employee в некорректном состоянии и/или введение уже созданного объекта в некорректное состояние.

## Задание 2

### Основное 

Создать класс Ring (кольцо) на основе Round (см. задание 2 из предыдущей темы), описываемое координатами центра, внешним и внутренним радиусами, а также свойствами, позволяющими узнать площадь кольца и суммарную длину внешней и внутренней границ кольца.

<strong>NOTE:</strong> Учесть, что внешний радиус должен быть больше внутреннего.

Класс должен содержать:

1.  Конструктор, который в качестве параметров принимает 4 целочисленных значения: внешний радиус, внутренний радиус и координаты центра.
2.  Свойства:

-   Radius – получение внешнего радиуса;
-   InnerRadius – получение внутреннего радиуса;
-   X – X-координата центра;
-   Y – Y-координата центра;
-   Circumference – получение суммарной длины внешней и внутренней границ кольца;
-   Area – получение площади.

### Требования

1.  Класс Ring должен быть унаследован от базового класса Round.
2.  Обеспечить нахождение класса в заведомо корректном состоянии.
3.  Продемонстрировать использование класса в консольном приложении.
4.  Продемонстрировать обработку сценариев с попытками создать объект класса Ring в некорректном состоянии и/или введение уже созданного объекта в некорректное состояние.
