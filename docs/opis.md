# Zadanie 2
`setContentView` - ustawia, co dany ekran będzie wyświetlać;

`findViewById`  - służy do znajdywania przez Id widoku w aktualnie wyświetlanym layoucie, jeżeli zdefiniowano przed `setContentView` lub popełniono literówkę, to zwrócone zostanie null;

`R` - jest to jakby wbudowania automatycznie "ścieżka", która tworzy z nazwy w XML pole w Javie; (P.S. nie wiem czy dobrze zrozumiałem)

`onCreate` - metoda systemowa, tworząca punkt startowy aplikacji;

`super.onCreate` - super to klasa nadrzędna, bez której aplikacja nie wystartuje;

`AndroidManifest.xml` - dokument, w którym znajdują się informację o aplikacji takie jak: jak się nazywa czy jakie ekrany posiada;

`@+id/` - identyfikator, przez który można znaleźć element po ID;

`match_parent` - kopiuje od rodzica ile miejsca ma zająć;

`dp` - jednostka, która jest automatycznie przeliczana by wyglądała tak samo na innych urządzeniach;

`sp` - podobna do `dp` z wyjątkiem dodatkowego skalowania rozmiaru czcionki wybranego przez użytkownika w systemie operacyjnym;
