我选了这本O'Reilly出版的书，出于2个考虑：第一，编程书入门一定要看英文版，第二，这本O'Reilly出版的书有相应的中文翻译版。O'Reilly出版社以动物为封面的计算机相关的书是计算机教材的权威，看了看书的目录，500多页，不算很厚，这个尺寸的书应该差不多可以涵盖所有的Python知识点。

接下来就是对照中英文目录，开始研究。

amazon.com  
amazon.cn  
oreilly.com  
http://openbookproject.net/thinkcs/python/english3e/  
python.org  

Number 数字  
String 字符串  
List 列表  
Dictionary 字典  
Tuple 元组  
Files 文件  

Array 数组  
要么是数，要么是字。  
数：数字。阿拉伯帝国  
字：字符，字符串。罗马帝国  

串，列，组，列表这些词表复数，如一串，一列，一组，一个列表。
xxxs变成xxxList

这个东西的大小，颜色，重量。This object。

Tuple诞生记  
1. 阳性单数主格拉丁词quintus"第五" --> 晚期拉丁语quintuplex"五倍" --> 法语`quintuple`  
`tu`来自quintus，是一步步遗传下来的，`祖传`
'ple'来自from a medieval Latin suffix ‑plus (meaning "more"[dubious – discuss]) related to Greek ‑πλοῦς, which replaced the classical and late antique ‑plex (meaning "folded"), as in "duplex".  
2. 然后模仿quintuple，造出了sextuple, septuple, octuple, ..., n‑tuple, ..., where the prefixes are taken from the Latin names of the numerals. 即后缀`-tuple`"表示多少倍的后缀"产生  
3. 最后单词`tuple`"中文翻译为元组"产生。即：The term originated as an abstraction of the sequence: single, double, triple, quadruple, quintuple, sextuple, septuple, octuple, ..., n‑tuple, ..., where the prefixes are taken from the Latin names of the numerals.  

阳性单数全部的格如下：
nominative	quin`tus` 主格  
genitive	  quin`t`ī  属格  
dative	    quin`t`ō  与格  
accusative	quin`t`um 宾格  
ablative	  quin`t`ō  夺格, 离格  
vocative	  quin`t`e  呼格  

![image](https://github.com/liaoleejun/learn-python/images/quintus.png)

number: five Quinque  
ordinal number: fifth quintus (Declension性数格：阳性单数主格)  
'ple' -ple -plex plus  
ord() ~~ ordinal ~~ ordinal numbers ~~~~~~ order  

Latin Numbers 1 - 10
One	Unum
Two	Duo
Three	Tres
Four	Quattuor
Five	Quinque
Six	Sex
Seven	Septem
Eight	Octo
Nine	Novem
Ten	Decem

Latin Numbers 1 - 10 in Roman Numerals
1 I
2	II
3	III
4	IV
5	V
6	VI
7	VII
8	VIII
9	IX
10	X

名词Noun Declension
动词Verb conjugation

可以指示名词、动词、形容词的叫（指示词性的）词缀吧
可以指示主属与宾夺呼的称为（指示格位的）词尾吧  
quintus中的tus叫它词尾吧，这样可以和英语的指示词性的词缀相区分开。然后tus一步步遗传下来，加上后缀-ple变成quintuple。tu是quintus的蛛丝马迹，痕迹，相貌遗传，`祖传`。
