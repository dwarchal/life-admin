# CLAUDE.md: zasady pracy w life-admin

Język: polski. Terminy techniczne po angielsku, z polskim tłumaczeniem obok.

## Dane
- Dane podaje Dawid. **Nie przeszukuj Gmaila** ani innych źródeł bez wyraźnej prośby.
- Zakres: tylko subskrypcje, umowy i rachunki Dawida (nie domowników), chyba że poprosi inaczej.
- Nie zapisuj haseł, pełnych numerów kart i kont ani numerów dokumentów (patrz README).
- Skany: tylko link do Google Drive.

## Aktualizacja
- Każda zmiana: aktualizacja tabeli i wpis w `decisions.md` (data, pozycja, decyzja, powód).
- Anulowana pozycja przechodzi z `active.md` do `cancelled.md`, z datą anulowania i datą końca dostępu.
- Commit z krótkim opisem po polsku.

## Przypomnienia (Google Calendar)
- Dla każdej pozycji z terminem wypowiedzenia: osobne wydarzenia całodniowe w dniach
  T−1 mies., T−14 dni, T−7 dni i T−1 dzień, gdzie T = termin wypowiedzenia.
  Gdy jest „najwcześniejszy dzień”, dodaj też wydarzenie w tym dniu.
- Własny zestaw w kolumnie „Przypomnienia” ma pierwszeństwo przed domyślnym.
- Tytuł wydarzenia: `[life-admin] <nazwa>: wypowiedzenie do <T>`. W opisie: koszt, link do anulowania, link do repo.
- Po przedłużeniu lub zmianie terminu: usuń stare wydarzenia, utwórz nowe.

## Comiesięczny przegląd (1. dzień miesiąca)
- Lista pozycji z terminami w ciągu 60 dni, pozycje ze statusem `do przeglądu`
  i suma kosztów rocznych w CHF.
- Sprawdzenie, czy każda pozycja z terminem ma wydarzenia w kalendarzu.
