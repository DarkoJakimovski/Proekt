# Опис на проектот:

Проектот има за цел да создаде Flask апликација која може да ги прочисти имињата на компаниите со отстранување на несаканите
знаци и ознаки,нормализирање на имињата со големи букви само на првите букви од секој збор и акроними и зачувување на резултатот во MongoDB базата на податоци.


# Користени модули и методи:

GET метод - SQLite базата на податоци содржи табела наречена "companies" ;
POST метод - MongoDB базата на податоци ги складира прочистените податоци за секоја компанија во колекција наречена "cleaned_companies"


1. Flask: Микро веб-рамка напишана во Python која се користи за креирање на веб-апликации.
1.1 jsonify е функција обезбедена од Flask за конвертирање на Python објект во JSON-формат.
2. sqlite3: Модул кој се користи за интеракција со SQLite бази на податоци. Обезбедува функции за поврзување во базата на податоци.
3. pymongo: Модул кој се користи за интеракција со MongoDB бази на податоци.
4. requests: Модул кој се користи за испраќање HTTP барања во Python.
5. re: Модул кој се користи за работа со регуларни изрази во Python.
6. cleanco: Модул кој се користи за идентификување и отстранување ознаки на легални ентитети/правни лица од имињата на компаниите.



# Заклучок:
Проектот за прочистување на големи податоци со Flask апликација е корисна алатка за
чистење и нормализирање на имињата на компаниите и складирање на резултатите во MongoDB базата на податоци.
