# Aktualizacja 2.0
1. W Supabase SQL Editor wykonaj upgrade.sql (nie database.sql).
2. W GitHub zastąp app.js, index.html, style.css, config.js. Poczekaj na publikację i Ctrl+F5.
3. Generator kont tworzy dane dostępowe, nie tworzy Auth automatycznie. W Supabase Authentication > Users > Add user użyj wygenerowanego e-maila i hasła, Auto Confirm, skopiuj UID i przypisz w generatorze. Wyłącz publiczną rejestrację w Supabase. Nie używaj prawdziwych danych. Dokumenty są symulacją, bez zapisu w bazie. Drukowanie przez przeglądarkę. Plan tygodniowy ręczny z kontrolą kolizji; nie jest automatycznym optymalizatorem. Usuwanie klas i przedmiotów z zależnościami jest blokowane przez bazę. Test składni JS wykonany; brak testu na żywej bazie.
