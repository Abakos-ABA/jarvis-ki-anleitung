# Jarvis KI – Gratis-Kurzanleitung

Statische Seite fuer die Gratis-Kurzanleitung "Eigenen KI-Assistenten bauen", verlinkt vom
YouTube-Kanal "Jarvis KI" (@jarviski). Gehostet via GitHub Pages aus diesem Repo (main, root).

Seit 15.10.2026 (Marlon-Auftrag, Task 20261015-155144-c78b): die Seite zeigt jedem Besucher per
JavaScript einen eindeutigen Einmal-Code, geholt vom Dienst `jarvis-code-gate.service` auf dem
mailcow-VPS (`https://abakos.ai/jarvis-code/...`). Kommentiert der Besucher den Code unter einem Video
auf dem Kanal, schaltet der Kommentar-Waechter des Jarvis-Repos (`tools/jarvis_kanal_kommentare.py` +
`tools/jarvis_code_gate.py`) ihn frei - die Seite erkennt das per Polling und zeigt danach den vollen
Anleitungstext (kommt vom Dienst, steht nicht im Quelltext dieser Seite). Details, Architektur und
Dienst-API: `docs/jarvis-kanal-code-gate.md` im Jarvis-Repo.

Die alte, komplett offene Fassung (vor 15.10.2026 direkt unter `/` erreichbar) liegt zur Referenz noch
unter `/komplett/` - nicht mehr verlinkt, bewusst nicht geloescht (Marlon-Vorgabe).

Kein Verkauf, keine Nutzerkonten, keine Formulare - nur eine statische Seite + ein kleiner Freischalt-Dienst.
