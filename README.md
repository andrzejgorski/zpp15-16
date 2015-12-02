

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


##2. Co udalo się zrobić?

####Strona projektu z minutkami i dokumentami
https://github.com/andrzejgorski/zpp15-16

####Wybór języka - Polski

####Konfiguracja travisa W00t!!!
https://travis-ci.org/9livesdata/whylog/builds/93819751


###Dużo nowego kodu


#####Waiting for merge config access branch
https://github.com/9livesdata/whylog/commit/41594738a254fbfb881cb75bbe1f072881eddf4c


####Dyskusja nad kodem:

https://github.com/9livesdata/whylog/pull/20


####Przełożenie i przerobienie UML


https://github.com/9livesdata/whylog/commit/ccb289b2ffb35fd80f801e5192f5ca34276fabd7#commitcomment-14666061


#####Jednak klient nadal nie jest jeszcze szczęśliwy.



##3. Z czym jeszcze walczymy...
https://github.com/konefalg/whylog/blob/c66e09b015206863842ae2c893e80031febf28bf/whylog/client/__init__.py


##4. Co planujemy zrobić?

###1. Rozbicie Umla na kilka mniejszych fragmentów.
#####a) Struktura stanów. (Zależności pomiędzy nimi itp)
#####b) Wygląd wbudowanych widokow w poszczególnych stanach

###2. Rozpoczęcie implementacji Teachera


###3. Domergowanie config access layer (rule base)


###4. Dalsze implementacje klienta (pierwsze 3 testy)



