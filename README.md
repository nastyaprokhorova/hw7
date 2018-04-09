# Домашнее задание №7
##### Как лингвоспецифичное слово я выбрала слово *"скитаться"*. Для того, чтобы проверить и доказать мои предположения о лингвоспецифичности данного слова, я провела следующие исследования:
1. Работая в параллельном корпусе НКРЯ (*в англо-русском подкорпусе*), я проверила, сколько контекстов встречается на слово **"скитаться"**. Далее я проанализировала, как данное слово передано на другом языке и создала таблицу:

**Модели перевода**|**Частотности**
---|---
Не учитывается|24
Wander (ed/s/ings/er/ing)|1 (9/1/2/1/8) = 22
Grieving|1
Roaming (ed/ about/ among)|2 (1/1/1) = 5
Driven out (away)|2 (1) = 3
Quartering|1
Roved about|1
Ranges|1
Drifting (ed)|2 (2) = 4

2. Я посчитала меры разброса моделей перевода:
+ *отношение абсолютной частоты самой частотной модели перевода **(F (Mmax))** к количеству различных эквивалентов **(NumM)***;
Самой частотной моделью перевода получилось слово *«wander»* - **22 раза**. Количество различных эквивалентов *«скитаться»* - **8** (не включая вариант, где перевод слова пропущен). Исходя из этих данных получаем, что **F(Max)/(NumM) = 22/8 = 2,75**.
+ *средняя частота вхождений на один эквивалент **(F(O)/NumM**, где F (O) — частотность данного слова в оригинале)*;
Общее количество вхождений в корпус - **64**, количество различных эквивалентов - **8**. Отсюда получаем следующее: **F(O)/NumM = 64/8 = 8**.
+ *отношение абсолютной̆ частоты самой частотной модели перевода к частоте второй **(F(Mmax)/F(Msec))***;
Абсолютная частота самой частотной моделеи перевода (*'wander'*) - **22 раза**. Абсолютная частота второй по частотности модели перевода (*'roam'*) - **5 раз**. Отсюда получаем следующие данные: **F(Mmax)/F(Msec) = 22/5 = 4,4**.
+ *отношение абсолютной частоты самой частотной модели перевода к общему количеству вхождений **(F (Mmax)/F (O))***;
Абсолютная частота самой частотной модели перевода - **22**. Общее количество вхождений в корпус - **64**. Исходя из этой информации получаем следующие данные: **F(Mmax)/F(O) = 22/64 = 0,34**.

Просмотрев все данные можно сделать вывод, что слово «скитаться» является лингвоспецифичным, так как оно имеет много вариантов перевода, но ни один из них не передает смысл и окрас, который оно несет в русском языке, в полной мере. Исходя из количества моделей перевода и частоты их использования, можно сказать, что только одно из вышепредложенных слов (*'wander'*) близко по значению с русской версией (*'скитаться'*), а остальные почти не используются и далеки от необходимого значения.
