## Исследование объявлений о продаже квартир

В вашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 

## Выводы
В ходе работы была проведена предобработка данных - устранены некоторые пропуски, некорректные значения. Оптимизированы названия населенных пунктов. Скорее всего, часть некорректных и пропущенных значений является ошибками ввода или невозможностью обработать не полные данные.
Из полученного датасета можно сделать вывод, что в центре Петербурга квартиры дороже, чем на окраине или в городах-спутниках. Студии и однушки по цене квадратного метра являются лидерами, но при этом продаются быстрее всего. К тому же и количество их предложений самое большое.
Как по центру Санкт-Петербурга, так и по всей Ленобласти, наблюдается только корреляция между общей ценой объекта и его площадью, и между площадью и количеством комнат. Так же присутствует линейная зависимость цены от растояния до центра.

Для более точной оценки рыночной стоимости квартиры, на мой взгляд, следует учитывать и такие факторы, как расстояние до метро,  год постройки, наличие лифта, наличие газоснабжения, есть ли горячее водоснабжение. Стоимость квартиры при этом зависит от совокупности всех факторов.
