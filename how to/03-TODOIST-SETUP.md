# Konfiguracja Todoist

## Projekty

Utwórz projekt nadrzędny:

```text
💼 WORK
```

oraz podprojekty:

```text
🎯 Chapter Leader
👥 People
🏗 Team A
🏗 Team B
💡 Someday
```

Korzystaj z systemowego Inbox do szybkiego przechwytywania.

## Etykiety

Na start tylko:

```text
%deep
%quick
%waiting
%1on1
%followup
```

Znaczenie:

- `%deep` — zadanie wymagające skupienia.
- `%quick` — krótka czynność, zwykle 5–15 minut.
- `%waiting` — wykonuje ktoś inny; Ty kontrolujesz wynik.
- `%1on1` — temat do omówienia z konkretną osobą.
- `%followup` — musisz wrócić do sprawy.

## Priorytety

- P1 — wymaga uwagi dzisiaj / krytyczne.
- P2 — ważne, najbliższe dni.
- P3 — standardowa praca.
- P4 — backlog / bez presji.

Nie dawaj sztucznego terminu zadaniom tylko po to, żeby zobaczyć je w Today.

## Filtry — Command Center

### 🔥 ACTION

```text
(today | overdue) & ##WORK
```

### ⏳ WAITING

```text
%waiting & ##WORK
```

### 👥 PEOPLE

```text
%1on1 & ##WORK
```

### 🧠 DEEP

```text
%deep & ##WORK
```

Dodaj te filtry do Favorites.

## Przykłady

Twoje działanie:

```text
Omówić budżet z Pawłem tomorrow %quick
```

Delegacja / oczekiwanie:

```text
Marek — analiza problemu PROD Wednesday %waiting
```

Temat na 1:1:

```text
Tomek — ownership projektu XYZ %1on1
```
