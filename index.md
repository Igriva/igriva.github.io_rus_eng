---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Содержание
---
1.	[Russian](#rus)

1. 	[English](#eng)


# <a name="rus"></a>Russian


## Стандарт **Unicode**

**Unicode** – это промышленный стандарт кодирования для единого универсального цифрового представления символов всех письменностей мира, а также описания всех известных на сегодня областей знаний с используемыми в них обозначениями. 

Стандарт включает универсальный набор символов **UCS** (Universal Character Set) и набор кодировок **UTF** (Unicode Transformation Format), но часто, говоря о **Unicode**, имеют в виду именно первую часть стандарта – универсальный набор символов. Этот набор символов описывается кодовой таблицей, которая ставит в соответствие хранимым символам уникальные номера позиций в таблице. 

Номера будем называть кодовыми точками, они описываются неотрицательными целыми числами в шестнадцатеричной системе счисления с префиксом U+, например, буква ‘F’ имеет код U+0046. Эта таблица хранит символы всех современных алфавитов, устаревших и даже мертвых языков, иероглифы, специальные знаки, такие как элементы формул, музыкальные знаки, знаки валют и даже эмодзи.

### Предпосылки и история

Одной из самых ранних и употребимых кодовых таблица была **ASCII** (American Standart Code for Information Interchange), разработанная в США в 1963 году. В исходном семибитном варианте **ASCII** содержала заглавные и строчные буквы латинского алфавита, цифры, знаки препинания и управляющие символы, она представлена в таблице 1. Например, в этой кодовой таблице символ ‘F’ имеет номер 100 0110<sub>2</sub> или 46<sub>16</sub>. Аббревиатуры используются в ней для обозначения управляющих и непечатных символов, не имеющих графического представления. Первые 128 символов кодировки **ASCII** были перенесены в **Unicode** в неизменном виде, их номера в двух кодовых таблицах совпадают. 

Позже стал использоваться 8 битный вариант **ASCII**, что привело к увеличение таблицы вдвое. Вторая половина таблицы из 128 символов использовалась для хранения национальных алфавитов. Небольшой объем таблицы не позволял хранить сразу несколько национальных алфавитов, что привело к появлению различных национальных вариантов таблицы **ASCII**. Такой подход исключал представления многоязыковых текстов и создавал существенные трудности при попытке использовать текст из другой кодовой таблицы. Кроме того, нашлись языки, количество букв в алфавитах которых превышало количество доступных позиций во второй половине таблицы. Также возникали сложности, связанные с использованием шрифтов, так как для каждой национальной кодировки создавался свой шрифт, даже при условии, что многие символы в разных национальных кодировках совпадали. Неоспоримым плюсом **ASCII** и других восьмибитных кодировок является фиксированная длина представления каждого символа и крайняя экономичность.

# <a name="eng"></a>English

## **Unicode** standard

**Unicode** is an industrial coding standard for a uniform universal digital representation of all the written languages characters, as well as a description of all knowledge areas with the them notation.

The standard includes the universal character set **UCS** (Universal Character Set) and the character encoding systems **UTF** (Unicode Transformation Format). Nevertheless, speaking of **Unicode** we usually mean the first part of the standard - the universal character set. A code table describes this set. The table maps the stored characters to unique position numbers.

We will call the numbers code points. These code points are described by non-negative hexadecimal integers with the prefix U+, for example, the letter ‘F’ has the code U+0046. The code table stores the characters of all modern alphabets, obsolete and even dead languages, hieroglyphs, special signs such as formula elements, musical signs, currency signs, and even emojis.

### Background and history

**ASCII** (American Standard Code for Information Interchange) is the one of the earliest and most commonly used code tables. It was developed in the USA in 1963. Initial seven-bit version **ASCII** contained uppercase and lowercase letters of the Latin alphabet, numbers, punctuation and control characters. The one is presented in table 1. For example, in this code table the character 'F' has the number 100 0110<sub>2</sub> or 46<sub>16</sub>. Abbreviations like NUL or DC1 denote control and non-printable characters that do not have a graphic representation. The first 128 characters of the **ASCII** were transferred to **Unicode** unchanged, their numbers in the two code tables are the same.

Later the 8-bit version **ASCII** was used, which led to a doubling of the table. The second half of the table consists of 128-character and uses for national alphabets storing. The small size of the table did not allow storing several national alphabets at once. As a result, various national versions of the **ASCII** table appeared. This approach excluded multilingual texts representation and created significant difficulties when using text from another code table. In addition the alphabets of some languages contain more letters than the position numbers in the second half of the table. Also some difficulties associated with the use of fonts. The fonts were created for each national encoding, although many characters in different national encodings coincided. The indisputable advantages of **ASCII** and other eight-bit encodings are a fixed character representation length and extreme thrift.


### Table 1. Code table **ASCII**

!["ASCII"](/images/ascii.png)
