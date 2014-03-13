# placeMarkers (Позиционни маркери) #

* Автори: Noelia, Chris.
* Изтегляне [стабилна версия][1]
* Изтегляне [работна версия][2]

Тази добавка се използва за запазване и търсене на определен текст или
отметка в уеб страници или други документи в режим на разглеждане с
NVDA. Може също да бъде използвана за запазване или търсене на текстове в
многоредови контроли; в този случай опресняването на каретката не е
възможно, затова отговарящият низ ще бъде копиран в клипборда, така че да
може да бъде намерен с други инструменти.  Добавката записва низовете и
отметките в текстови и pickle файлове. Имената на тези файлове са базирани
на името и URL адреса на текущия документ.

Тази добавка е базирана на SpecificSearch и Bookmark&Search, разработени от
същия автор. Ако смятате да използвате тази добавка, трябва първо да
премахнете горните две, тъй като те имат сходни клавишни команди и
възможности.

## Клавишни команди: ##

*	control+shift+NVDA+s; Отваря диалогов прозорец, който ви позволява да запазите текстов низ за търсене в текущия документ. По подразбиране се показва предишно запазеният текст за този файл. Изтрийте този текст и натиснете бутона Ok, ако искате да премахнете текстовия файл, отговарящ на запазеното търсене, или въведете нов текст, за да добавите друго търсене.
*	control+shift+NVDA+f; Отваря диалогов прозорец с поле за писане, който съдържа последно запазеното търсене; в този диалог можете също и да изберете някое от предишните търсения (от първия падащ списък) и да изберете действие (от следващия падащ списък). Ако няма налични файлове за конкретно търсене в текущия документ, NVDA ще ви предупреди, че няма намерен файл за конкретно търсене.
*	control+shift+NVDA+k; Запазва текущата позиция като отметка
*	control+shift+NVDA+delete; изтрива отметката, отговаряща на тази позиция.
*	control+shift+k; Премества курсора до следваща отметка.
*	shift+NVDA+k; Премества курсора до предишна отметка.
*	NVDA+k; Копира в клипборда името на файла (без разширението), където ще бъдат съхранени данните за позиционните маркери.

## Подменю Позиционни маркери (NVDA+N) ##


Използвайки подменю Позиционни маркери, намиращо се в подменю Настройки от
главното меню на NVDA, имате достъп до:

*	Папка за конкретно търсене: отваря папката, където са записани предишните
  конкретни търсения.
*	Папка с отметки; отваря папката със запазените отметки.
*	Копиране на папката с позиционни маркери; можете да копирате папката с
  позиционни маркери на друго място на твърдия диск.
*	Възстановяване на позиционните маркери; може да възстановите вашите
  позиционни маркери от предишно съхранено копие на папката с вашите
  позиционни маркери.
*	Файл с документация, на вашия майчин език (ако е наличен), или на
  английски (по подразбиране).

Забележка: позицията на отметките се базира на броя на знаците; поради това
в страници с динамично съдържание е по-добре да използвате конкретното
търсене вместо отметките, които запазват точно определена позиция.


## Промени във версия 3.0 ##
* Добавена е поддръжка за бегло четене.

## Промени във версия 2.0 ##
* Добавени са опции за запазване и изтриване на различните търсения за всеки
  файл.
* Отстранен е проблем с пътищата на файловата система, които съдържат
  символи, различни от латиница.
* Бързите клавиши вече могат да бъдат преназначавани с използване на диалога
  Жестове на въвеждане на NVDA.


## Промени във версия 1.0 ##
* Първоначално издание.
* Добавката е преведена на: бразилски португалски, фарси, фински, френски,
  галицийски, немски, италиански, японски, корейски, непалски, португалски,
  испански, словашки, словенски, Тамил.

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=pm

[2]: http://addons.nvda-project.org/files/get.php?file=pm-dev