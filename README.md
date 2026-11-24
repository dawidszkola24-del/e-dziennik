# e-Dziennik PRO ONLINE
Symulator szkoły, niezależny od Librusa. Wyłącznie fikcyjne dane.

1. W istniejącym projekcie Supabase uruchom **update.sql** w SQL Editor (raz). Nie uruchamiaj ponownie database.sql: to pierwotna instalacja, dołączona jako referencja.
2. W Authentication wyłącz publiczną rejestrację (Allow new users to sign up). Konta twórz ręcznie w Users, z potwierdzeniem e-mail. Nie publikuj haseł.
3. Wgraj index.html, style.css, app.js, config.js do głównego katalogu repozytorium. Settings > Pages > Deploy from a branch > main > / (root) > Save.
4. Otwórz adres GitHub Pages, zaloguj się e-mailem i hasłem istniejącego administratora.
5. Utwórz konta nauczycieli, rodziców i uczniów w Authentication. Skopiuj UID i przypisz role w module Konta. Dodaj klasy, uczniów (powiąż konta), przedmioty i nauczycieli. Zaloguj się jako nauczyciel, dodaj temat, zatwierdź obecność, dodaj oceny. Przetestuj oddzielne konta ucznia i rodzica.

Ograniczenia: prototyp nieprzetestowany na żywej bazie. Nie używać prawdziwych danych. Brak archiwizacji lat, automatycznych zastępstw, pełnej edycji/usuwania rekordów, plusów/minusów, oficjalnych świadectw, automatycznego tworzenia kont Auth z aplikacji. Plan jest listą datowanych wpisów. Frekwencja: obecny i spóźniony liczone jako obecność, zwolnienia wyłączone z mianownika. Świadectwo jest symulacją; średnia z ocen rocznych bez wag. W istniejącej bazie katalog nazw kont jest widoczny dla użytkowników z rolą. Wymagany audyt RLS i testy przed jakimkolwiek rzeczywistym wdrożeniem. Publiczny klucz Supabase nie jest tajnym kluczem; nigdy nie umieszczaj service_role w repozytorium.
