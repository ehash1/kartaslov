# Экспериментальные срезы (открытая семантика русского языка)

Срезы, которые мы пометили как "экспериментальные", служат фундаментом и пищей для планирования дальнейшей работы, но могут быть менее полными и/или точными. Их много, поэтому мы вынесли их описание отдельно, в данный документ.

## Идея датасета, его формат и структура

Подробное описание идеи датасета, его формата и структуры записи смотрите здесь: [открытая семантика русского языка (датасет)](../).

## Срез "CLASS:BT/DISHES/FOOD" (экспериментальный)

Еда представляет собой отдельный, очень важный в жизни каждого человека, класс материальных сущностей. Слова в этом срезе распределяются по следующим категориям:

* FOOD — еда и напитки;
* DISHES — посуда;
* BT — бытовая техника.

N.B. Т.к. вопросы в данном срезе строились от еды, то категория бытовой техники (BT) попадает сюда по касательной к основной разметке и доверять её следует осторожно. Что касается еды и посуды, то там всё хорошо.

## Срез "CLASS:MOVE" (экспериментальный)

Разметка глаголов (в основном) и существительных с точки зрения того, содержится ли в них смысловой компонент движения. Последнее понимается в широком смысле — перемещение, изменение положения тела и другое.

* YES — имеет отношение к движению
* NO — не имеет отношения к движению

## Срез "TEZ:REL_TYPE" (экспериментальный)

Разметка отношений между понятиями.

* VERTICAL — понятия находятся в отношении ОБЩЕЕ-ЧАСТНОЕ;
* PART/WHOLE — понятия находятся в отношении ЧАСТЬ-ЦЕЛОЕ;
* SYN — понятия являются синонимами.

## Срез "CLASS:KIN" (экспериментальный)

Разметка слов, выражающих отношение родства.

* YES — является отношением родства;
* PARTIAL — частично является отношением родства;
* NO — не является отношением родства;

## Срез "CLASS:WEATHER" (экспериментальный)

Разметка погоды, погодных явлений и времён суток.

* GOOD_WEATHER — хорошая погода;
* BAD_WEATHER — плохая погода;
* TIME_OF_DAY — время суток;

Это был один из самых спорных срезов с точки зрения формулировок вопросов и предполагаемой логики разметки. В ответы попадает много сущностей, не относящихся к погоде, но связанных с ней. Интересен как эксперимент.

