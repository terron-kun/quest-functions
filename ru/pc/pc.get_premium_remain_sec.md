# pc.get_premium_remain_sec()
Функция **pc.get_premium_remain_sec** сообщает оставшееся количество секунд определенного премиум-баффа.

## Параметры функции
### premium_index
Тип *number*. **Обязательный параметр**. Индекс премиум-баффа.

## Возвращаемые значения
### remain_sec
Тип *mixed*. Количество оставшихся секунд.

Если указан неверный индекс премиум-баффа или если он не является числом, то возвращается `nil`, то бишь ничего.

## Примечания
Функция **не** может быть вызвана анонимно.

Баффы хранятся в базе данных в таблице `account.account`. Существуют следующие индексы премиум-баффов:

| Индекс | Название | Название в БД | Значение |
| --- | --- | --- | --- |
| 0 | PREMIUM_EXP | gold_expire | Бонус к получаемому опыту |
| 1 | PREMIUM_ITEM | silver_expire | Бонус к дропу |
| 2 | PREMIUM_SAFEBOX | safebox_expire | Дополнительные ячейки на складе |
| 3 | PREMIUM_AUTOLOOT | autoloot_expire | Автоматический подъем выпадающих янг |
| 4 | PREMIUM_FISH_MIND | fish_mind_expire | Повышенная вероятность поймать редкую рыбу (возможна неточность) |
| 5 | PREMIUM_MARRIAGE_FAST | marriage_fast_expire | Повышенная скорость получения свадебных очков любви |
| 6 | PREMIUM_GOLD | money_drop_rate_expire | Повышенный дроп янг |