# life-admin

Prywatne repo do spraw domowo-papierowych: **subskrypcje**, **umowy** (contracts), **rachunki** (bills) i terminy ich wypowiedzenia lub przedłużenia.

## Struktura

| Ścieżka | Co zawiera |
|---|---|
| `subscriptions/active.md` | tabela aktywnych subskrypcji |
| `subscriptions/cancelled.md` | archiwum anulowanych (żeby nie wróciły po cichu) |
| `contracts/` | umowy, jeden plik na umowę (dodamy później) |
| `bills/` | rachunki cykliczne (dodamy później) |
| `decisions.md` | dziennik decyzji: co, kiedy i dlaczego |
| `CLAUDE.md` | zasady pracy dla Claude |

## Zasady (prywatność)

- Repo jest **prywatne**.
- **Nigdy**: hasła, pełne numery kart, numery kont (IBAN), numery dokumentów tożsamości.
- Metoda płatności tylko jako np. „karta UBS …1234”, „PayPal”, „App Store”.
- Skany umów i rachunków (PDF) leżą w **Google Drive**. W repo jest tylko link.

## Terminy i przypomnienia

Każda pozycja ma:
- **termin wypowiedzenia**: ostatni dzień, w którym można wypowiedzieć,
- **najwcześniejszy dzień wypowiedzenia** (opcjonalnie), np. „nie wcześniej niż miesiąc przed”.

Domyślne przypomnienia: **1 miesiąc, 2 tygodnie, 1 tydzień i 1 dzień** przed terminem wypowiedzenia. Gdy jest najwcześniejszy dzień, dochodzi przypomnienie w dniu, w którym okno się otwiera. Pozycja może mieć własny zestaw (kolumna „Przypomnienia”).

Przypomnienia są w Google Calendar, jako osobne wydarzenie dla każdego przypomnienia. Dodatkowo 1. dnia każdego miesiąca jest przegląd repo z listą terminów na najbliższe 60 dni.
