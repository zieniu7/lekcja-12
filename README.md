# lekcja-12
🔹 parent()

Co robi?
Wskazuje bezpośredniego opiekuna elementu — ten, który jest o jeden poziom wyżej.

Zastosowanie w kodzie:
Znajdujemy rodzica akapitu i zmieniamy mu tło.

🔹 parents()

Co robi?
Pokazuje całą rodzinę w górę — wszystkich przodków aż do samego szczytu dokumentu.

Zastosowanie:
Podświetlamy wszystkich przodków wybranego <p>.

🔹 children()

Co robi?
Pokazuje dzieci elementu — co znajduje się bezpośrednio w środku.

Zastosowanie:
Podświetlamy wszystkie elementy znajdujące się wewnątrz #nestedDiv.

🔹 siblings()

Co robi?
Pokazuje braci i siostry elementu — inne elementy na tym samym poziomie.

Zastosowanie:
Po kliknięciu w <li> podświetlamy pozostałe elementy tej samej listy.

🔹 addClass()

Co robi?
Nadaje elementowi klasę CSS (czyli nowy wygląd).

Zastosowanie:
Kliknięty <li> dostaje klasę active.

🔹 removeClass()

Co robi?
Usuwa wskazaną klasę CSS.

Zastosowanie:
Przed zaznaczeniem nowego elementu usuwamy klasę active ze wszystkich innych.

🔹 toggleClass()

Co robi?
Włącza lub wyłącza jakąś klasę — jak przełącznik.

Zastosowanie:
Przyciski do zadań 2 przełączają wyróżnienie elementów.

🔹 find()

Co robi?
Przeszukuje wnętrze elementu i znajduje wszystkie pasujące elementy (nawet głęboko schowane).

Zastosowanie:

znalezienie wszystkich <span> i pokolorowanie ich na czerwono,

znalezienie wszystkich linków i nadanie im target="_blank".

🔹 attr()

Co robi?
Ustawia atrybut HTML — np. href, src, target.

Zastosowanie:
Dodajemy linkom otwieranie w nowej karcie.

🔹 map()

Co robi?
Przerabia kolekcję elementów na listę wartości.

Zastosowanie:
Z przodków wyciągamy same nazwy tagów (div, body itd.).

🔹 get()

Co robi?
Zwraca zwykłą tablicę z elementami.

Zastosowanie:
Potrzebne, żeby złączyć nazwy tagów w jedną linię tekstu.

🔹 text()

Co robi?
Ustawia tekst wewnątrz elementu.

Zastosowanie:
Wyświetlamy nazwy przodków lub dzieci w polu wynikowym.
