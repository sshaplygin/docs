#### Фильтрация результатов {#filter}

Поле `filter` содержит правило фильтрации результатов поиска и определяет, исключать ли из результатов поиска какие-либо документы. Возможные значения:

* `none` — фильтрация отключена. В выдачу включаются любые документы вне зависимости от содержимого.
* `moderate` — умеренный фильтр (значение по умолчанию). Из выдачи исключаются документы, относящиеся к категории "для взрослых", если запрос явно не направлен на поиск подобных ресурсов.
* `strict` — семейный фильтр. Вне зависимости от поискового запроса из выдачи исключаются документы, относящиеся к категории "для взрослых", а также содержащие ненормативную лексику.