# Release-Plan: Campus App

## Ziel

Das Team bereitet **Version 1.0** für die Veröffentlichung am Freitag vor.

## Aufgaben

- Vorbereitung abgeschlossen
  - [x] Repository klonen
  - [x] Lokalen main aktualisieren
- Umsetzung noch offen
  - [] Navigation testen
  - [] Profilseite prüfen
  - [] README ergänzen

## Teamübersicht

| Bereich     | Verantwortlich | Status     |
|-------------|----------------|------------|
| Navigation  | Julian         | Fertig     |
| Profilseite | Ben            | In Arbeit  |
| Tests       | Tom            | Offen      |

## Geplanter Ablauf

### 1. Main aktualisieren
```sh
git switch main
git pull
```
### 2. Arbeitsbranch erstellen
```sh
git switch -c release-check
```
### 3. Änderungen prüfen und speichern
```sh
git status
git add .
git commit -m "Prepare release"
```
> Hinweis: Direkte Änderungen auf ```main``` vermeiden. Für jede Aufgabe wird ein eigener Branch verwendet.

## Dokumentation

[GitHub Flow](https://docs.github.com/de/get-started/using-github/github-flow)