# Machine Learning - Laboratories

* **Course**: Machine Learning (DUMZ UI0 1CA/1CB)
* **School**: Adam Mickiewicz University in Poznan, Faculty of Mathematics and Computer Science
* **Instructor**: Roman Grundkiewicz, Krzysztof Jassem
* **CyberAcademy**: https://cyberacademy.wmi.amu.edu.pl/modules?courseId=29

The official information about the course can be found here:
https://ramy15.wmi.amu.edu.pl/ (unfortunatelly no direct link available).


## Praca na laboratorium

### Inicjalizacja repozytorium

Przed pierwszym użyciem należy utworzyć własne repozytorium korzystając z
zaproszenia. Link do zaproszenia dostępny na
[CyberAcademy](https://cyberacademy.wmi.amu.edu.pl/sections?moduleId=36)

Po zaakceptowaniu zaproszenia zostanie utworzone repozytorium
`http://github.com/amuumz/umz2016-<github_username>`, gdzie `<github_username>`
to login GitHub.

Sklonowanie swojego repozytorium (z wiersza linii poleceń Linux):

    git clone https://github.com/amuumz/umz2016-<github_username>

Dodanie repozytorium _matki_:

    git remote add mother https://github.com/amuumz/umz2016

### IPython Notebook

Uruchomienie Jupytera z poziomu wiersza linii poleceń:

    jupyter notebook

### Wysyłanie rozwiązań

    git add labs/01/lab01-numpy-zadania.ipynb
    git commit -m "Rozwiązania zadań z laboratorium 01"
    git push origin master

### Aktualizowanie repozytorium

Na początku każdych następnych ćwiczeń należy pobrać nowe notatniki:

    git pull mother master


