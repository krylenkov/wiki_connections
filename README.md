# wiki_connections
connections between people on the basis of the wiki

Wikipedia has special templates to describe a person. These templates may contain information on the person’s connections with other people. These connections depend on the wikipedia language and could include familiar relationships: parents/children/spouses, master-apprentice relationships, predecessor-follower relationships in governing and so on.

That means that wikipedia could be seen as a repository of information on relationships between a large number of individuals. It should be possible to extract and analyze this information.

This structured description is easy to extract and represent as an xml file. That’s exactly what I did, using English and Russian wikipedia dumps as my starting points.


This makes a wide area of research possible:
Building genealogical trees
Finding shortest links between historical figures
Finding the number of royal dynasties with a given number of generations
Extracting subsets of persons based on any other conditions.


Representing the data as a structure of relationships allows to verify the correctness of data in wiki-articles and to automatically detect errors. For example we have already found a number of cases with loops in familiar relationships, e.g. when a grandson is listed as the father of his grandfather, with children being born before their parents or hundreds of years after their deaths.

Вообще же я думаю о том, что следует создать надстройку над вики, где можно было бы просто задавать различные возможные виды связи между людьми (дружба, отношения и т.д.). Уверен, это позволило бы намного эффективнее анализировать различные социалные явления, исторические процессы.

Going forward, it would be useful to create a data layer on top of a wiki that would simplify defining different kinds connections between people, such as friendships, relationships, etc. I am sure it would make it easier to research social phenomena and historical processes.

Examples

The biggest cluster of people connected only through marriage or romantic relationships:

https://drive.google.com/file/d/0B1GlOLveSFDpTUpEQ3A5YU0tMGs/view

А вот самая длинная по числу поколений монархическая династия: 
The longest (by the number of generations) royal dynasty:

https://drive.google.com/file/d/0B1GlOLveSFDpRW5BVFMyNHFBRGc/view

More details about this project could be found in the following articles (in Russian):

https://goo.gl/qllSjZ
https://goo.gl/iyQ7kH


================================
В различных языковых разделах википедии существуют специальные шаблоны описания людей, в которых может быть указана какая-либо их связь с другими людьми.  Типов подобных связей множество: это и родственные отношения: родители/дети/супруги, это и связи учитель-ученик, предшественник-преемник по властным полномочиям и некоторые другие.

Таким образом в википедии содержатся данные по множеству людей связанных между собой и эти данные можно и нужно как-то использовать. 

Это структурированное описание легко вытащить и представить в виде xml файла, что и было мной проделано из дампа английской и русской вики.  

Поле для деятельности обширно: строить генеалогические деревья, искать кратчайшие связи между историческими персонажами, подсчитывать количество монархических династий по длине поколений, вытаскивать различые подмножества людей по любым иным условиям.

Представление данных в виде структуры связей позволяет проверять и корректность заполнения многих вики-статей.   Можно автоматизированно выявлять ошибки: и множество их уже было обнаружено, например петли родственных связей, когда внук указан в виде отца своего дедушки. Или когда дети рождаются до рождения родителей или через сотни лет после (для этого использовались еще данные о годах рождений).

Вот например самый большой кластер людей, связанных между собой исключительно узами брака или партнерскими отношениями:

Подробнее можно прочитать в двух моих заметках (русский язык):
https://goo.gl/qllSjZ
https://goo.gl/iyQ7kH

