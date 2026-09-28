# Konfiguracja Obsidiana

## 1. Docelowa struktura vaulta

```text
Chapter Leader OS/
├── 00 Inbox/
├── 01 Daily/
├── 02 Meetings/
│   ├── Team A/
│   ├── Team B/
│   ├── Management/
│   └── Other/
├── 03 People/
├── 04 Teams/
├── 05 Projects/
├── 06 Decisions/
├── 07 Leadership/
├── 08 Weekly Reviews/
└── templates/
```

Repo zawiera katalog `templates/`. Możesz otworzyć całe repo jako vault albo skopiować katalog `templates` do istniejącego vaulta.

## 2. Core plugin Templates

W Obsidian:

1. Settings → Core plugins → włącz **Templates**.
2. Settings → Templates → **Template folder location** → `templates`.
3. Opcjonalnie ustaw hotkey dla `Templates: Insert template`.

## 3. Daily Notes

1. Settings → Core plugins → włącz **Daily notes**.
2. New file location → `01 Daily`.
3. Date format → `YYYY-MM-DD`.
4. Template file location → `templates/Daily`.
5. Opcjonalnie ustaw hotkey dla `Daily notes: Open today's daily note`.

## 4. Pozostałe template'y

Twórz normalną notatkę w odpowiednim katalogu, a następnie użyj `Templates: Insert template`:

- ważne spotkanie → `Meeting`
- 1:1 → `1on1`
- profil osoby → `Person`
- istotna decyzja → `Decision`
- piątkowy przegląd → `Weekly-Review`

Nie twórz osobnego pliku dla każdego zwykłego daily/refinementu. Takie spotkania zapisuj w Daily Note.

## 5. Oznaczenia na spotkaniach

```text
D: Decision
A: Action
F: Follow-up
R: Risk
B: Blocker
?: Open Question
```

Przykład:

```markdown
## 10:00 Architecture Sync

R: API może nie być gotowe na release.
D: Nie czekamy na API v2.
A: Marek → analiza v1.
A: Ja → rozmowa z PO.
F: Sprawdzić status w środę.
?: Czy Security zaakceptuje rozwiązanie?
```

Najważniejsze: nie rób stenogramu. Zapisuj to, co zmienia decyzje, odpowiedzialność albo dalsze działania.
