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

## Zwykły text w mathmodzie

<http://tex.stackexchange.com/questions/19502/is-there-a-preference-of-when-to-use-text-and-mathrm>

W większości przypadków, z którymi się spotkałem w naszym repo powinno się używać właśnie `\text{}`.
Nie ma też sensu zagnieżdżać mathmode jak np. było parę razy `\textrm{blabla $x + 2$}` - należy
po prostu skończyć komendę wcześniej i skorzystać z zewnętrznego mathmodea, w którym już jesteśmy.
