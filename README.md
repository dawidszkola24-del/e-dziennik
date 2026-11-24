# e-Dziennik PRO 3.0
1. Wykonaj upgrade3.sql w Supabase SQL Editor (po aktualizacji 2.0).
2. Wgraj index.html, app.js, style.css, config.js i README.md do głównego katalogu GitHub. Nie publikuj SQL.
3. Poczekaj na Pages, Ctrl+F5. Wybierz właściwy portal logowania.
4. Generator dyrekcji: administrator generuje dane, tworzy użytkownika w Supabase Authentication (Auto Confirm), kopiuje UID i przypisuje profil w generatorze. To nie jest automatyczne tworzenie Auth.
5. Oceny: nauczyciel przypisany do przedmiotu, temat i zatwierdzona obecność, następnie Oceny. Średnia ważona, +/- przy liczbie to 0,5 (ograniczenie 1–6); samodzielne znaki i nb/bz/np pomijane. Klasyfikacja pozostaje całkowita.
6. Terminarz: miesiące 2026–2027, plus przy dniu, kolor wydarzenia. Wydarzenia zapisują się w bazie.
Tylko fikcyjne dane. Nie testowano na działającym Supabase. Zachowano wcześniejsze RLS i moduły; wykonaj testy ról. Nie umieszczaj tajnych kluczy w repozytorium.
