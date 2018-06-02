# hw8
## Задание 1

Использовала регулярное выражение: (\s?\r\n){2,}. Заменила все вхождения на \r\n, тем самым удалив все пустые строки:

![](https://github.com/mmyakubova/hw8/blob/master/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201.png)

См. также прикрепленный файл result.txt.

## Задание 2

Использовала регулярное выражение: [А-Я][а-яѣ]*слав[а-яѣ]*. Обнаружила 592 упоминания о князьях и городах, имя и название которых оканчивается на "слав":

![](https://github.com/mmyakubova/hw8/blob/master/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%202.png)

## Задание 3

Использовала регулярное выражение: Нов(ѣ|ъ|а|у)?город(ѣ|ъ|цю|а|у|е|ом)?. Нашла 59 упоминаний о Новгороде:

![](https://github.com/mmyakubova/hw8/blob/master/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%203.png)

## Бонус
Предприняла попытку поставить пробелы после каждого знака препинания (в соответствии с правилами русского языка). Для этого использовала регулярное выражение: ([А-Яа-яѣ]+\\.)|([А-Яа-яѣ]+:)|([А-Яа-яѣ]+,)|([А-Яа-яѣ]+;). Вхождения заменила на \1 \2 \3 \4 (после каждой цифры - пробел):

![](https://github.com/mmyakubova/hw8/blob/master/%D0%91%D0%BE%D0%BD%D1%83%D1%81.png)

Результат моей попытки можно также найти в файле Бонус.txt.
