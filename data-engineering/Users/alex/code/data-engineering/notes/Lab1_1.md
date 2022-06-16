[[build_steps_dashboard|Назад]]
___
# Что есть грануляция данных - ?
## What Does Granular Data Mean?

Granular data is detailed data, or the lowest level that data can be in a target set. It refers to the size that data fields are divided into, in short how detail-oriented a single field is. A good example of data granularity is how a name field is subdivided, if it is contained in a single field or subdivided into its constituents such as first name, middle name and last name. As the data becomes more subdivided and specific, it is also considered more granular.
## Techopedia Explains Granular Data

Granular data, as the name suggests, is data that is in pieces, as small as possible, in order to be more defined and detailed. The advantage of granular data is that it can be molded in any way that the data scientist or analyst requires, just like granules of sand that conform to their container. Granular data can be aggregated and disaggregated to meet the needs of different situations.

If data is not granulated, such as a name or address field being saved as a whole, then it is very difficult for analysts to mine and analyze data because they are in large chunks. Granular data can be easily merged with data from external sources and can be effectively integrated and managed.

На представленном ниже скриншоте гранулярность минимальна:
![[Pasted image 20220527214616.png]] Всего из 16 полей-метрик две "гранулы" - по 12 и 4 поля:
- первая - OrderID (поля от OrderDate до PostalCode - 11шт - описывают конкретный заказ). Итого 12 полей в одной "грануле".
- вторая - ProductID (поля от Category до ProductName 3 шт. - описывают конкретный продукт). Итого 4 поля в другой "грануле".
Еще 4 поля (Sales, Quantity, Discount, Profit) - измерения

# Шпаргалки по созданию визуализаций
![[выбор визуализации данных.jpg]][[выбор визуализации данных.jpg]]
# Обработка файла Ексель
[Файл Ексель с лабораторной](obsidian://open?vault=data-engineering&file=Users%2Falex%2Fcode%2Fdata-engineering%2Flabs%2FModule01%2FSampleSuperstore.xls)