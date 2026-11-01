# Plan rozbudowy (1.11.2026, pomysły Marzeny po pierwszym użyciu)

Zasada bez zmian: każdy chwyt tylko z cytatem albo „brak”; bez punktacji.

1. **Katalog chwytów z nazwy**, żeby model nazywał, nie opisywał:
   - Cialdini: wzajemność, zobowiązanie i konsekwencja, dowód społeczny, autorytet, sympatia, niedobór.
   - Chris Voss (negocjacje): lustrowanie, etykietowanie emocji („wygląda na to, że…”), pytania kalibrowane („jak mam to zrobić?”), audyt oskarżeń (uprzedzanie zarzutów), „to prawda” vs „masz rację”, awersja do straty, kotwica cenowa, deadline jako dźwignia.
   - NLP i pokrewne: presupozycje („kiedy już się zgodzisz…”), polecenia wbudowane, fałszywa alternatywa („wolisz A czy B?”), uogólnienia („wszyscy”, „zawsze”, „nikt”), czytanie w myślach („wiem, że czujesz…”), utrata nominalizacji (kto konkretnie? kiedy?).
   - Pisma urzędowe i firmowe: strona bierna bez sprawcy, „zgodnie z procedurą” bez wskazania procedury, termin bez podstawy, groźba w trybie warunkowym.
2. **Drobny druczek** jako osobna, szósta część: warunki schowane w zdaniach podrzędnych („o ile”, „chyba że”, „z zastrzeżeniem”), domyślne ustawienia („brak odpowiedzi oznacza zgodę”), terminy i co się dzieje po ich upływie, koszty wymienione nie wprost, kto ponosi ryzyko, co można odwołać, a czego nie.
3. Rozejrzeć się po literaturze, zanim katalog urośnie: lepiej 20 chwytów z dobrymi nazwami niż 80 z nazwami wymyślonymi.
4. Ewentualnie: wybór trybu (mail prywatny / umowa / pismo urzędowe / post publiczny), bo w każdym inne chwyty są typowe.

## Osobna appka: dla starszych ludzi (pomysł Marzeny, 1.11.2026)
Duże litery, jeden wynik: **UWAGA** albo **WYGLĄDA W PORZĄDKU**, z zastrzeżeniem. Bez klucza i bez czatu, bo starsza osoba nie będzie kopiować do modelu: wersja regułowa, offline, nic nie opuszcza telefonu. Oszustwa są schematyczne, więc reguły tu działają (inaczej niż przy manipulacji w ogóle): prośba o kod BLIK / SMS / hasło, przelew „na bezpieczne konto”, podszywanie się pod bank / policję / wnuka / kuriera / urząd, link do kliknięcia, „nikomu nie mów”, „natychmiast / dziś / w ciągu godziny”, obietnica zysku, przesyłka z dopłatą. Każdy sygnał pokazany dużymi literami jako powód. Zawsze ta sama rada na dole: „Zanim cokolwiek zrobisz, zadzwoń do kogoś, komu ufasz. Bank i policja nigdy nie proszą o kod ani przelew.” Zastrzeżenie: to nie gwarancja; brak sygnałów nie znaczy, że bezpieczne. Źródło listy schematów: ostrzeżenia Policji, CERT Polska, ZBP; sprawdzić, zanim się wpisze.

### Podpięcie do telefonu (pytanie 1.11): SMS i połączenia
- **SMS, Android:** wykonalne. Aplikacja czyta przychodzące SMS-y (jako domyślna aplikacja SMS albo przez dostęp do powiadomień) i pokazuje własne, duże ostrzeżenie. Reguły na urządzeniu, nic nie wychodzi. Dystrybucja: Google Play ogranicza uprawnienia do SMS, więc albo sklep po przejściu weryfikacji, albo plik APK instalowany ręcznie (dla rodziny).
- **SMS, iPhone:** tylko „rozszerzenie filtrujące” (Message Filter Extension): może klasyfikować wiadomości od nieznanych nadawców do folderów (np. „Śmieci”, „Transakcje”), bez własnego ostrzeżenia na ekranie. Słabsze.
- **Połączenia, nieznany numer:** Android: CallScreeningService, aplikacja może oznaczyć i zablokować połączenie po numerze (baza zgłoszonych numerów). iPhone: Call Directory Extension, to samo, po liście numerów. Oba bez słuchania.
- **Słuchanie rozmowy na żywo:** nie dla aplikacji firm trzecich. Android od wersji 10 nie daje dostępu do audio rozmowy, iPhone nigdy nie dawał. Robi to tylko producent telefonu (Google Pixel ma wykrywanie oszustw na urządzeniu, na razie nie po polsku).
- Co już istnieje: filtry spamu w Wiadomościach Google i Samsung Smart Call, blokady spoofingu u operatorów (CERT/UKE), ostrzeżenia w aplikacjach banków. Luka: ostrzeżenie po polsku, wielkimi literami, z powodem, które starsza osoba rozumie.
- Wniosek: strona WWW tego nie zrobi; potrzebna aplikacja natywna, najpierw Android. To projekt na tygodnie, nie wieczór; wersja WWW (wklej tekst) to krok pierwszy i test reguł.
