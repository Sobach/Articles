# Ко дню рождения смайла

Утром 19 сентября 1982 года Скотт Фалман опубликовал в университетской BBS'ке такое сообщение:

    ----------------------------
    19-Sep-82 11:44 Scott E Fahlman :-)
    From: Scott E Fahlman <Fahlman at Cmu-20c>
    I propose that the following character sequence for joke markers:
    :-)
    Read it sideways. Actually, it is probably more economical to mark
    things that are NOT jokes, given current trends. For this, use
    :-(

    ----------------------------

[оригинал того сообщения](http://www.cs.cmu.edu/~sef/Orig-Smiley.htm)

Различные варианты использования стандартной типографики для изображения эмоций предлагались и ранее:

* А.Бирсом в 1912 году:

> "an improvement in punctuation – the snigger point, or note of cachinnation: it is written 
thus \\\_\_\_/! and presents a smiling mouth" ([Wikipedia](http://en.wikipedia.org/wiki/Emoticon#cite_note-5));

* В.Набоковым в 1969 году:

> "I often think there should exist a special typographical sign for a smile -- some sort of 
concave mark, a supine round bracket, which I would now like to trace in reply to your question" 
([The New York Times](http://lib.ru/NABOKOW/Inter11.txt_with-big-pictures.html)).

Однако на сегодняшний день именно 19 сентября является "официальным" днем рождения смайла. Приятно, что сам 
я -- хоть и всего на 1 день -- но старше смайла.

За 31 год "джентельменский набор" смайлов заметно расширился по сравнению с "двоеточием-дефисом-скобкой" и довольно 
глупо выглядят рассуждения о том, что без смайлов общение в сети было бы совсем другим... (ваш КО, да). 
Поэтому я опускаю всю патетику по теме и перехожу сразу к результатам несерьезного (как и требуют обстоятельства) 
исследования под условным названием "пара слов про смайлы в московском твиттере".

С 1 по 31 августа с помощью [Twitter filter stream](https://dev.twitter.com/docs/api/1.1/post/statuses/filter) 
я старательно собирал все твиты, о которых было известно, что их писали в Москве и ближайших окрестностях. 
Всего получилось около 1 млн твитов (999&nbsp;620). Из них 20,7% содержали что-то похожее на смайлы 
(распознавание смайлов было сделано с помощью регулярных выражений).

В процессе сбора встретилось много всего, в том числе, и странного (может кто-то сможет обогатить свой смайло-набор):

![Smiles cloud](https://dl.dropboxusercontent.com/u/81437006/img_github/smile_cloud.png)

## Корреляции-результаты-выводы

Смайлы -- это перенесенные на экран эмоции, а эмоции -- это прежде всего межличностное общение. 
Можно предположить, что в face-to-face твитах смайлов должно быть больше. Эта гипотеза подтверждается. 
65% твитов со смайлами содержат в тексте упоминания других пользователей (mention) -- т.е., речь идет 
либо о персональном обращении, ответе (reply), либо ретвите (retweet). Среди сообщений без смайлов упоминания 
пользователей встречаются лишь в 41% случаев.

![Smiles-mentions correlation](https://dl.dropboxusercontent.com/u/81437006/img_github/smiles_mentions.png)
