baduk-pros-DB
=============

A database with information about Korean baduk([game of Go](http://en.wikipedia.org/wiki/Go_%28game%29)) professionals in sqlite3 and other formats. Information extracted automatically from [the Hankuk Kiwon website](http://baduk.or.kr/info/player1.asp).
Manual modifications and updates by Julio Martinez.

##Fields
* _id_: Original id number from Hankuk Kiwon website.
* _koreanName_: Name in Korean, written in Hangul (sometimes ending with 大 or 小, in case of people with same name).
* _englishName_: Romanization of the Korean name; in some cases using old romanization, in other cases modern.
* _chineseName_: Hanja (Han characters) of the Korean name.
* _dan_: Current dan level as professional.
* _birthdate_: Date when the professional was born.
* _danYear_: Year when the player became professional.
* _picture_: URL to a picture.
