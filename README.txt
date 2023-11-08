## Testy automatyczne w Postman

To repozytorium zawiera kolekcję testów automatycznych napisanych w narzędziu Postman. Testy te służą do weryfikacji odpowiedzi otrzymanych podczas wykonywania zapytań HTTP do określonego API lub usługi sieciowej. Każdy test jest opisany w postaci funkcji w języku JavaScript i wykorzystuje wbudowane w Postman narzędzia do weryfikacji odpowiedzi i nagłówków.

Poniżej znajduje się lista przetestowanych aspektów:

### 1. Weryfikacja kodu statusu odpowiedzi
Test sprawdza, czy kod statusu odpowiedzi HTTP jest równy 200 lub 404 i czy jest to liczba całkowita.

### 2. Weryfikacja czasu odpowiedzi
Test sprawdza, czy czas odpowiedzi jest mniejszy niż 200 ms.

### 3. Weryfikacja statusu odpowiedzi
Test sprawdza, czy status odpowiedzi jest równy "OK" i czy jest to ciąg znaków.

### 4. Weryfikacja ID posta
Test sprawdza, czy ID pierwszego posta w odpowiedzi jest równe 1 i czy jest to liczba całkowita.

### 5. Weryfikacja długości nazwy
Test sprawdza, czy długość nazwy drugiego obiektu w odpowiedzi wynosi 41 znaków.

### 6. Weryfikacja adresu e-mail w odpowiedzi
Test sprawdza, czy każdy adres e-mail w odpowiedzi zawiera znak "@".

### 7. Weryfikacja nagłówków
Test sprawdza obecność nagłówka "Content-Encoding" w odpowiedzi.

### 8. Weryfikacja wartości nagłówka "Server"
Test sprawdza, czy wartość nagłówka "Server" wynosi "cloudflare".

Te testy automatyczne pomagają w zapewnieniu poprawności i spójności odpowiedzi API lub usługi sieciowej, co jest istotne w procesie automatycznego testowania i monitorowania aplikacji. Dzięki nim można wykryć potencjalne błędy i problemy z wydajnością na wczesnym etapie rozwoju oraz automatycznie monitorować zachowanie aplikacji w czasie rzeczywistym.
