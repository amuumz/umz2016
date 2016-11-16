Gratka flats challenge
======================

Zadanie konkursowe jest dostępne na platformie [Gonito.net](http://gonito.net)
pod nazwą [mieszkania](http://gonito.net/challenge/mieszkania). Konkurs polega
na zbudowaniu najlepszego modelu przewidującego cenę mieszkania na zestawie
testowym.

Dane zapisane są w formacie `.tsv`. Cena mieszkań jest wyrażona w 1000 zł.

Repozytorium
------------

1. Stwórz grupę składającą się z maksymalnie trzech osób, wybierz lidera grupy
   i nazwę dla grupy (bez polskich znaków).
1. Lider grupy klika w link aktywacyjny (podany przez prowadzącego), w którym
   wpisuje nazwę swojej grupy.
1. Lider grupy zgłasza prowadzącemu: nazwę grupy i loginy GitHub jej członków.
1. Każdy z członków grupy klonuje wspólne repozytorium, np.:

   ```
   git clone https://github.com/amuumz/umz2016-mieszkania-<nazwa_grupy>.git
   ```

   i pracuje nad rozwiązaniem, ostatecznie wrzucając je do repozytorium:

   ```
   git add test-A/out.tsv
   git add <pliki_z_rozwiazaniem>
   git commit -m "<sensowny_komentarz>"
   git pull origin master
   git push origin master
   ```

Gonito.net
----------

1. Utwórz konto na platformie Gonito.net, jeżeli jeszcze nie posiadasz.
1. Opcjonalnie (tylko na komputerach osobistych) zainstaluj program `geval` do
   ewaluacji lokalnej wg instrukcji w _Install GEval_ na stronie wyzwania
   [mieszkania](http://gonito.net/challenge/mieszkania).
1. Uwaga: proszę nie wykonywać **bezpośrednio** poleceń z dalszej części
   instrukcji w _How To_, gdyż wykorzystujemy własne repozytoria.
1. Po opracowaniu własnego rozwiązania, umieść je jako plik `test-A/out.tsv`.
   Kod źródłowy również należy umieścić w repozytorium.

1. Wyślij rozwiązanie na Gonito.net korzystając z formularza
   [Submit](http://gonito.net/challenge-submission/mieszkania). W opisie podaj
   nazwę swojego zespołu i krótki opis rozwiązania, np. `myteam: linear
   regression baseline`, jako URL podaj adres repozytorium grupy:

   ```
   https://github.com/amuumz/umz2016-mieszkania-<nazwa_grupy>.git
   ```
