# Laby-Delfina-i-Alicja

Czym jest polimorfizm? Jest to jedno z podstawowych założeń programowania obiektowego. Oznacza możliwość używania jednej nazwy metody do wykonywania różnych operacji, w zależności od typu obiektu. Dzięki temu można obsługiwać różne obiekty w jednolity sposób, bez znajomości ich szczegółowej implementacji. 

Wyróżniamy dwa główne rodzaje polimorfizmu:

- Statyczny - polega na przeciążeniu metod i operatorów. Oznacza to, że w jednej klasie może istnieć wiele metod o tej samej nazwie, ale różniących się listą parametrów. Wybór odpowiedniej metody następuje w czasie kompilacji na podstawie liczby i typów argumentów. Nie jest możliwe przeciążanie metod różniących się wyłącznie typem zwracanym.

  
- Dynamiczny - polega na nadpisywaniu metod w klasach pochodnych (override). Jest związany z dziedziczeniem i wykorzystuje mechanizm wiązania dynamicznego, co oznacza, że wybór odpowiedniej metody następuje w czasie działania programu, na podstawie rzeczywistego typu obiektu. 
