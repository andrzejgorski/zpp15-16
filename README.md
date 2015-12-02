

#Whylog prezentacja:

##1. Minutka z poprzedniego tygodnia

Minutka

1. Data, czas i miejsce spotkania

26.11.2015, 8:30
MIMUW

2. Osoby obecne

Ewa Pawłowska
Andrzej Górski
Krzysztof Gromadzki
Grzegorz Konefał

3. DONE

- konfiguracja nosetests
- wybór licencji BSD 3-clause
- przebudowa warstwy dostępu do danych
- zaprojektowanie nowych klas odpowiedzialnych za reguły i parsery
- wstępny wybrany temat: Whylog Efektywne Przeszukiwanie Logów

4. TODO (na następne zajęcia)

- Strona projektu z linkami do minutek i dokumentami (github) - Krzysiek
- Przygotowanie prezentacji kodu: - Andrzej
    - struktura katalogów
    - zaprezentowanie kodu
- rozpoczęcie implementacji regex creatora teachera - Ewa
- dokończenie UMLa - Andrzej
- merge do mastera brancha configaccess - Krzysiek
- prototyp klienta przechodzi pierwsze 3 testy - Grzesiek
- wybór języka dokumentacji (angielski lub polski)

5. Ustalenia

- branch dev i master z działającym kodem
- repozytorium z kodem na githubie:
    https://github.com/9livesdata/whylog

- przygotowanie prezentacji o vimie 14 I 2015
- strona projektu z minutkami i informacjami o projekcie oraz dokumentacją:
    https://github.com/andrzejgorski/zpp15-16

####1. ó) o Projekcie:
https://github.com/9livesdata/whylog/tree/master/whylog

##2. Co udalo się zrobić?

![alt tag](http://www.photos-public-domain.com/wp-content/uploads/2012/08/done.jpg)

#####1. Strona projektu z minutkami i dokumentami
```
Ta strona :D
```
https://github.com/andrzejgorski/zpp15-16

#####2. Wybór języka - Polski

#####3. Konfiguracja travisa W00t!!!
```
Nadprogramowe
```
https://travis-ci.org/9livesdata/whylog/builds/93819751


#####4. Dużo nowego kodu


######Waiting for merge config access branch
https://github.com/9livesdata/whylog/commit/41594738a254fbfb881cb75bbe1f072881eddf4c


######Dyskusja nad kodem:

https://github.com/9livesdata/whylog/pull/20


#####5. Pierwsze zalążki tego co będzie w przyszłości naszą pracą licencjacką

https://9livesdatazpp.slack.com/files/konefalg/F0FNRDFEV/Co_chce_brac_i_co_chce_dac


#####6. Wprowadzony nowy standard prezentacji
```
To ta prezentacja
```

#####7. Przełożenie i przerobienie UML


https://github.com/9livesdata/whylog/commit/ccb289b2ffb35fd80f801e5192f5ca34276fabd7#commitcomment-14666061



#####Jednak klient cały czas zgłasza własne uwagi z których możemy czerpać naukę.


##3. Z czym jeszcze walczymy...
![alt tag](http://www.dobroni.pl/foto_galeria/dsc_0337dig.jpg)

#####Implementacja clienta. Dotychczasowy kod przechodzi jak narazie jeden test.

https://github.com/konefalg/whylog/blob/c66e09b015206863842ae2c893e80031febf28bf/whylog/client/__init__.py


#####Jednak się nie poddajemy. :D


##4. Co planujemy zrobić?
![alt tag](http://i.imgur.com/OvMZBs9.jpg)

#####1. Rozbicie Umla na kilka mniejszych fragmentów. - Andrzej
######- Struktura stanów. (Zależności pomiędzy nimi itp)
######- Wygląd wbudowanych widokow w poszczególnych stanach

#####2. Rozpoczęcie implementacji Teachera - Ewa

#####3. Domergowanie config access layer (rule base) - Krzysiek

#####4. Dalsze implementacje klienta (pierwsze 3 testy) - Grzesiek

#####5. Rozpoczęcie pisania dokumentów do pracy w oparciu o szablon - Andrzej

