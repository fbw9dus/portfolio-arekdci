# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

- Seite nur für mobile
- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- Link für Email, der E-Mail Anwendung öffnet (4/5)
```diff
- Der link funktioniert, aber ein mailto-Link muss mindestens die Empfänger-Adresse enthalten
```
- Link für Telefon, der Telefon-Anwendung öffnet (5/5)
- Link zum Lebenslauf(PDF), der einen Download auslöst (4/5)
```diff
- Der Link ist da und hat das download attribut. Wäre schön, wenn im Pfad zumindest ein Dateiname stehen würde.
```
- Links zu Social Media Profilen
  - Haben Icons der Dienste (10/10)
  - Sollen in einem neuen Tab öffnen (5/5)
  
- Foto, das im Kreis dargestellt wird, mit border-radius (5/5)
- Navigation zu den Abschnitten mit Hash-Links (10/10)
- Bilder im Portfolio sollen verlinkt sein (0/10)

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (10/10)
- Padding in den Links der Hauptnavigation (10/10)
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (7/10)
```diff
- Sehr wenig Abstand zum Fensterrand beim letzten Link bei Kontakt
```
- Korrekte html-Grundstruktur (html, head, body) (10/10)
- Keine Viewport-Elemente im head (5/5)

### Punkte
(**85**/100)
