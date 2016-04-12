# Kompilacja
Należy kompilować plik `zadania_rozwiązania.tex`, on includuje pliki poszczególnych tygodni, jako wynik dostajemy pdf,
w którym są rozwiązania zadań tylko z obecnego tygodnia (dyrektywa `\includeonly{...}` w głównym pliku to kontroluje).

# Dodawanie zadania
Należy edytować plik `zad_xx.tex`, gdzie `xx` jest numerem zadania, które powinno się zrobić. Rama rozwiazania wygląda tak:
```
\subsection{Zadanie xx}

<treść>

```

Treść powinna być czystym kodem latexa, bez żadnych dodatkowych środowisk, które zawierałyby całe zadanie (typu `\begin{zad}`).

# Losowe wskazówki

## Łamanie linii

<http://tex.stackexchange.com/questions/153506/insert-a-new-line-without-newline-command/#153595>

Generalnie używanie `\newline` i podobnych to raczej ostateczność.
