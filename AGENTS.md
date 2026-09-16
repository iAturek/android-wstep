# Zasady projektu

Projekt szkolny – Android, klasa 5 technikum programisty.

## Technologie – obowiązkowe

- Język: **Java** (nie Kotlin)
- Interfejs: **layouty XML** (nie Jetpack Compose)
- Dostęp do widoków: **findViewById** (nie View Binding, nie Data Binding)
- minSdk 24, kompilacja pod aktualne SDK z szablonu

## Jak masz pracować

- Małe kroki. Jedna zmiana naraz, potem czekasz na moje potwierdzenie.
- Nie dodawaj bibliotek bez pytania.
- Nie zmieniaj plików Gradle bez pytania.
- Nie zmieniaj plików, o które nie prosiłem.
- Komentarze w kodzie po polsku, krótkie, tylko tam gdzie coś nieoczywistego.
- Nazwy w kodzie **po angielsku** – klasy, metody, zmienne, id w XML, nazwy zasobów.

## Czego NIE robisz

- Nie commitujesz. Commity robię sam.
- Nie uruchamiasz `git push`, `git reset --hard`, `rm -rf`.
- Nie generujesz całych ekranów naraz – mam to rozumieć linia po linii.

## Konwencja nazw

- Wszystkie identyfikatory po angielsku: klasy, metody, zmienne, id widoków,
  nazwy zasobów. Po polsku tylko teksty widoczne dla użytkownika i komentarze.
- id widoków: `btnSave`, `tvResult`, `etName`, `ivLogo`
- pola klasy odpowiadają id: `private Button btnSave;`
- nazwy w `strings.xml` po angielsku, wartości po polsku:
  `<string name="error_empty_name">Najpierw wpisz imię</string>`
