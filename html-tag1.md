# HTML-Kurs Tag 1: Grundlagen und erste Schritte

## Die wichtigsten HTML-Tags

### Grundstruktur
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Seitentitel</title>
</head>
<body>
    <!-- Hier kommt der sichtbare Inhalt -->
</body>
</html>
```

### Überschriften und Text
```html
<h1>Hauptüberschrift</h1>
<h2>Unterüberschrift</h2>
<p>Das ist ein Absatz mit Text.</p>
<br> <!-- Zeilenumbruch -->
<hr> <!-- Horizontale Linie -->
```

### Links
```html
<a href="https://www.example.com">Externer Link</a>
<a href="seite2.html">Interner Link</a>
<a href="#abschnitt">Link zu Abschnitt</a>
```

### Listen
```html
<!-- Ungeordnete Liste -->
<ul>
    <li>Punkt 1</li>
    <li>Punkt 2</li>
</ul>

<!-- Geordnete Liste -->
<ol>
    <li>Erster Schritt</li>
    <li>Zweiter Schritt</li>
</ol>
```

### Bilder
```html
<img src="bild.jpg" alt="Beschreibung des Bildes" width="300">
```

---

## Übung 1: "Meine erste Webseite" 

### Aufgabenstellung
Erstelle eine persönliche Vorstellungsseite mit folgenden Elementen:

1. **Überschrift** mit deinem Namen (h1)
2. **Unterüberschrift** "Über mich" (h2)
3. **Zwei Absätze** mit Text über dich
4. **Eine weitere Unterüberschrift** "Meine Interessen" (h2)
5. **Eine ungeordnete Liste** mit mindestens 3 Hobbys/Interessen

### Beispielstruktur
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Über [Dein Name]</title>
</head>
<body>
    <h1>[Dein Name]</h1>
    <h2>Über mich</h2>
    <p>Hier schreibst du etwas über dich...</p>
    <p>Ein zweiter Absatz mit weiteren Informationen...</p>
    
    <h2>Meine Interessen</h2>
    <ul>
        <li>Hobby 1</li>
        <li>Hobby 2</li>
        <li>Hobby 3</li>
    </ul>
</body>
</html>
```

---

## Übung 2: "Website-Rallye" 

### Aufgabenstellung für 2er-Teams

**Ziel:** Erstellt zwei verlinkte HTML-Seiten, die sich gegenseitig referenzieren.

#### Person A erstellt: `teamseite.html`
- **h1-Überschrift:** "Unser Team"
- **Kurze Vorstellung** des Teams (1 Absatz)
- **Teammitglieder** als geordnete Liste
- **Link** zur Hobbys-Seite
- **Ein Bild** (kann ein Platzhalter sein)

#### Person B erstellt: `hobbys.html`
- **h1-Überschrift:** "Unsere gemeinsamen Interessen"
- **Liste der Hobbys** (mindestens 5) als ungeordnete Liste
- **Link** zurück zur Teamseite
- **Horizontale Linie** zwischen Abschnitten
- **Kontakt-Abschnitt** mit E-Mail-Link

### Beispiel für Verlinkung
```html
<!-- In teamseite.html -->
<a href="hobbys.html">Zu unseren Hobbys</a>

<!-- In hobbys.html -->
<a href="teamseite.html">Zurück zur Teamseite</a>
```

### Bonus-Aufgaben
- Verwendet verschiedene Überschriftenebenen (h1, h2, h3)
- Fügt einen E-Mail-Link ein: `<a href="mailto:email@example.com">Kontakt</a>`
- Erstellt eine Navigation mit mehreren Links in einer Liste

---

## Tipps für heute

### Häufige Fehler vermeiden
- ✅ Alle Tags schließen: `<p>Text</p>`
- ✅ Anführungszeichen bei Attributen: `href="link.html"`
- ✅ Alt-Text bei Bildern nicht vergessen
- ✅ Dateipfade richtig angeben (Groß-/Kleinschreibung beachten)


### Ressourcen für Bilder
- [Unsplash](https://unsplash.com) - Kostenlose Bilder
- [Placeholder.com](https://placeholder.com) - Platzhalter-Bilder
- Beispiel: `<img src="https://via.placeholder.com/300x200" alt="Platzhalter">`
