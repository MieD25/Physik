# Physik – Interaktive Lerneinheiten

Interaktive Lerneinheiten für den Physikunterricht. Jede Einheit ist eine einzelne, eigenständige HTML-Datei (HTML, CSS und JavaScript inline, keine externen Bibliotheken) und läuft direkt im Browser.

**Startseite:** https://mied25.github.io/Physik/

## Einheiten

| Einheit | Kurs | Inhalt | Link |
|---|---|---|---|
| Impuls und Kraft | LK 11 · Mechanik | Impuls p = m·v, Impuls als Vektor, Stöße und Impulserhaltung, Impulsleiter/-isolatoren/-pumpen, Fließgleichgewicht, Rückstoß, Trägheit (1. Axiom), Wechselwirkung (3. Axiom), Kraft als Impulsstromstärke, Grundgleichung F = m·a (2. Axiom) | [impuls-kraft/](https://mied25.github.io/Physik/impuls-kraft/) |

## Aufbau einer Einheit

- Lernlandkarte (Advance Organizer) mit Kernfrage, Teilbereichen, Leitfragen und empfohlenem Lernpfad
- pro Leitfrage: Erklärung, Kernsatz, interaktive Simulation (Schritt für Schritt oder automatisch), Musterantwort
- Abschlussquiz mit Erklärungen
- Lernfortschritt wird nur lokal im Browser gespeichert (localStorage)

## Struktur

```
/index.html              Startseite mit allen Einheiten
/impuls-kraft/index.html Lerneinheit „Impuls und Kraft“
/.nojekyll               GitHub Pages ohne Jekyll ausliefern
```
