# item.change_rare_attribute()
Функция **item.change_rare_attribute** меняет 6-7 бонусы на &laquo;выделенном&raquo; предмете.

## Возвращаемые значения
### status
Тип *mixed*. Если предмет не был &laquo;выделен&raquo;, то ничего не возвращается, то бишь `nil`.

Если была совершена попытка изменить бонусы на костюме или если на предмете нет 6-7 бонусов, то возвращается `false` <sup>boolean</sup>. В случае успешного изменения бонусов возвращается `true` <sup>boolean</sup>.

## Примечания
Функция **не** может быть вызвана анонимно.

Эта функция работает только с &laquo;выделенными&raquo; предметами. Подробнее тут: [item](../item).