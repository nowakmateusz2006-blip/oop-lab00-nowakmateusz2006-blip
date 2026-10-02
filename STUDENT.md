# Moje wykonanie Lab00

- Login GitHub / pseudonim: nowakmateusz2006-blip
- System i terminal (np. Windows + WSL Ubuntu): Linux Mint Cinnamon
- Edytor / IDE: GitHub
- Wersja Git: 2.43.0
- Wersja kompilatora C++: 13.3.0
- Wersje java i javac: 21.0.10, 17.0.20.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): ...

## Uruchomienie lokalne
Wynik programu C++:
```
Hello from C++! Author: nowakmateusz2006-blip
```
Wynik programu Java:
```
Hello from Java! Author: nowakmateusz2006-blip
```

## Błąd i poprawka (zadanie 5)

- Krótki fragment komunikatu błędu i numer linii: cpp/main.cpp:5:73: error: expected ';' before 'return'
- Przyczyna oraz sposób naprawy: Brak średnika ; na końcu linii 5; dodanie ;
- Commit z błędem (SHA lub link): 3c2de88
- Czy Actions pokazały błąd, a po naprawie sukces? Tak

- Krótki fragment komunikatu błędu i numer linii: `cpp/main.cpp:5:73: error: expected ';' before 'return'` (linia 5)
- Przyczyna oraz sposób naprawy: Brak średnika `;` na końcu instrukcji `std::cout`. Naprawa polega na dopisaniu `;` na końcu linii 5.
- Commit z błędem (SHA lub link): Wprowadzenie błędu braku średnika w C++
- Czy Actions pokazały błąd, a po naprawie sukces? Tak, Actions wygenerowały błąd (exit code 1), a po naprawieniu i wypchnięciu kodu wynik był zielony.


## Krótkie odpowiedzi
1. Co różni commit od push? commit to lokalne zapisanie zmian w kodzie, a push to wyslanie tych zapisanych zmian na serwer zdalny.
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Git pull wykonuje się, aby zaktualizować lokalny kod o zmiany scalone na serwerze i uniknąć konfliktów w przyszłości.
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Zielony wynik CI potwierdza, że kod pomyślnie przeszedł automatyczne testy i buduje się bez błędów, ale nie gwarantuje braku ukrytych bugów logicznych oraz poprawnego działania po scaleniu z główną gałęzią.

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: ...
