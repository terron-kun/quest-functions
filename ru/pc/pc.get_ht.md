# pc.get_ht()
Функция **pc.get_ht** сообщает, сколько у игрока очков здоровья (не ХП, а статус).

## Возвращаемые значения
### status_amount
Тип *number*. Количество единиц очков статуса.

## Примечания
Функция **не** может быть вызвана анонимно.

Данная функция возвращает реальное количество очков статуса. Очки, полученные за счет [affect](../affect).* функций, снаряжения и других источников не считаются.