Задача №1 - "Радиоман"

Легенда

В рамках проекта по созданию "Умного дома" у нас появился очень важный клиент, которых хочет кастомную доработку: он очень любит радио, поэтому нам нужно научиться управлять радио.

Что нужно сделать: по аналогии с кондиционером создайте класс Radio, в котором храните следующие поля (т.е. данные, которые будут помнить о себе объекты радио):

Номер текущей (прослушиваемой) радиостанции
Громкость звука
Требования к работе с радиостанциями:

Номер текущей радиостанции изменяется в пределах от 0 до 9
Если текущая радиостанция - 9 и клиент нажал на кнопку next (следующая) на пульте, то текущей должна стать 0-ая (создайте отдельный метод для этой операции)
Если текущая радиостанция - 0 и клиент нажал на кнопку prev (предыдущая) на пульте, то текущей должна стать 9-ая (создайте отдельный метод для этой операции)
Клиент должен иметь возможность выставлять номер радиостанции с цифрового пульта (вводя числа 0 - 9) (сделайте сеттер)
Требования к работе с уровнем громкости звука:

Клиент должен иметь возможность увеличивать и уменьшать уровень громкости звука (в пределах от 0 до 10)*
Если уровень громкости звука достиг максимального значения, то дальнейшее нажатие на + не должно ни к чему приводить (создайте отдельный метод для этой операции)
Если уровень громкости звука достиг минимального значения, то дальнейшее нажатие на - не должно ни к чему приводить (создайте отдельный метод для этой операции)
