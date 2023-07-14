# DWH_design
Задание на проектирование DWH (КХД) в рамках курса "Инженер данных"

Cоставлена ER-диаграмма по схеме "Снежинка" по ссылке: (<code>[./ER-diagram.png](https://github.com/AlexeyAnanchenko/DWH_design/blob/main/ER-diagram.png)</code>)

### Входные данные:

- Информация о продажах (id заказа, время продажи, название товара, цена, бренд, модель товара, категория, cookies покупателя, сумма)						

- Информация о личных кабинетах покупателей (id личного кабинета, cookies покупателя, ФИО, пол, дата рождения, email, телефон)

- Информация о промо-акциях (id промо-акции, id товара, дата начала промо, дата окончания промо, размер скидки)

- Данные о прохождении баннерной рекламы: (id баннера, id товара, площадка размещения, cookies пользователя, тип действия (просмотр или клик), время действия).


На выходе должно быть возможно составить витрину в формате:

- id личного кабинета

- Пол

- Категория возраста

- Электронная почта

- Телефон

- Товар, который чаще всего покупал клиент за последний месяц

- Бренд и категория товаров, которые чаще всего покупал клиент

- Сумма, потраченная клиентом за месяц

- Количество товаров, купленных со скидкой

- Количество просмотренных баннеров

- Количество кликов на баннеры

- Средний CTR (отношение кликов к просмотрам) за месяц

- Категория товаров, на которые клиенты чаще всего кликают

- Активность клиентов в выходные или будние дни

- Трёхчасовой интервал с максимальной активностью