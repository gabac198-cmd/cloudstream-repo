# CloudStream repo — Filmotip

Repozitorij za CloudStream s pluginom **Filmotip**.

## Datoteke
- `repo.json`    – manifest repozitorija (ovaj link upisuješ u CloudStream)
- `plugins.json` – popis dodataka
- `FilmotipPlugin.cs3` – sam plugin

## Link za CloudStream
```
https://raw.githubusercontent.com/gabac198-cmd/cloudstream-repo/main/repo.json
```

## Kako ubaciti datoteke na GitHub
1. Otvori repozitorij `cloudstream-repo`.
2. Klikni **Add file** → **Upload files**.
3. Povuci `repo.json`, `plugins.json` i `FilmotipPlugin.cs3`.
4. Klikni **Commit changes**.

## Kako dodati u CloudStream
1. Otvori CloudStream.
2. **Settings** → **Extensions** (Dodaci).
3. **Add repository** (Dodaj repozitorij).
4. Zalijepi link iznad i potvrdi.

## Napomena
Plugin je veličine 43436 bajtova, a SHA-256 hash mora odgovarati vrijednosti
upisanoj u `plugins.json`, inače CloudStream odbije instalaciju.
