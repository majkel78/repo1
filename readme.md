# Podstawy programowania

### 1. Przygotowanie środowiska
- instalacja oprogramowania do wirtualizacji
- instalacja środowiska Linux (dystrybucja Ubuntu)

##### 2. Utworzenie katalogu projektu (w katalogu "Pulpit")


```sh
$ cd Pulpit
$ mkdir repo1
```

##### 3. Edycja plików projektu (edytor tekstu "Nano")

```sh
$ nano test.txt
```
##### 4. Instalacja i inicjalizacja systemu kontroli wersji "git"

```sh
$ apt install git
$ git init
```

##### 5. Utworzenie konta w serwisie "GitHub.com"

##### 6. Praca z systemem kontroli wersji (polecenia)

```sh
git help	(pomoc)
git init	(inicjalizacja)
git add .	(dodanie do systemu wszystkich plików z obecnego katalogu)
git add *.txt	(j.w. -> tylko pliki z rozszerzeniem txt)
git commit -m "komentarz"	(komentarz do plików dodanych poprzednią komendą)
git status	(status plików projektu - porównanie obecnych do ostatnio "zrzuconych")
git log		(wyświetlenie kolejnych komentarzy do zmian w projekcie)

git remote add origin https://github.com/majkel78/repo1.git
(powiązanie systemu "git" z kontem w serwisie "github.com")
git push -u origin master	(pierwsze przesłanie projektu do serwisu)
git push	(przesłanie aktualnej wersji projektu do serwisu)
```

##### 7. Plik "readme.md" w serwisie GitHub.com
