# pc.reset_status()
Функция **pc.reset_status** сбрасывает определенный статус до 1.

## Параметры функции
### status_index
Тип *number*. **Обязательный параметр**. Индекс статуса. `0` &mdash; здоровье; `1` &mdash; интеллект; `2` &mdash; сила; `3` &mdash; подвижность.

## Возвращаемые значения
### status
Тип *boolean*. Результат выполнения функции. `true`, если статы сбросились успешно; если параметр [status_index](#status_index) имеет неверное значение, то возвращается `false`.

## Примечания
Функция **не** может быть вызвана анонимно.

Сброшенные очки статуса возвращаются игроку и он может распределить их на свое усмотрение.