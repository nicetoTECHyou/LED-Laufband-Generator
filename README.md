🎨 Anpassbare Darstellung

Text-Eingabe: Freie Texteingabe (z. B. "HELLO WORLD!") mit Unterstützung für Großbuchstaben, Zahlen und Sonderzeichen (A-Z, 0-9, !, ?, ., ,, :).
LED-Farbe (An): Farbauswahl für aktive LED-Punkte (Standard: Rot #ff0000).
Hintergrundfarbe (Aus): Farbauswahl für inaktive LED-Punkte (Standard: Dunkelrot #220000).
Punktgröße: Einstellbar von 1 bis 10 Pixeln (Standard: 4).
Abstand zwischen Punkten: Einstellbar von 0 bis 5 Pixeln (Standard: 1).

⚡ Animation & Scrolling

Geschwindigkeit: Einstellbar über Slider (1-10, Standard: 5) für horizontales Scrolling des Textes.
Live-Vorschau: Echtzeit-Animation auf einem Canvas (60 Spalten x 7 Zeilen Matrix).
Nahtloses Scrolling: Text wiederholt sich endlos, mit Leerraum für flüssige Übergänge.

📤 Export-Funktionen

GIF-Export: Exportiert die Animation als GIF-Datei (led-marquee.gif).
Automatische Frame-Generierung basierend auf Textlänge.
Anpassbare Frame-Delay basierend auf Geschwindigkeit.
Verwendet gif.js-Bibliothek mit Worker-Unterstützung für Performance.

🎯 Benutzeroberfläche & UX

Dunkles Theme: Moderne, responsive UI mit schwarzem Hintergrund und grauen Akzenten.
Responsive Design: Zentrierte Container, funktioniert auf verschiedenen Bildschirmgrößen.
Statusanzeige: Live-Feedback während des Exports (z. B. "Rendere Frame X von Y").
Pixelated Rendering: Canvas mit pixeligem Stil für retro-LED-Look.

🔧 Technische Details

Font-System: Eingebaute 5x7 Dot-Matrix-Font (35 Zeichen definiert).
Canvas-Größe: Dynamisch angepasst basierend auf Punktgröße und Abstand.
Browser-Kompatibilität: Funktioniert in modernen Browsern mit Canvas- und Fetch-Unterstützung.
Lokaler Betrieb: Läuft offline als HTML-Datei (mit CORS-Workaround für GIF-Export).

🚀 Zusätzliche Features

Einfache Bedienung: Alle Einstellungen in einem Grid-Layout, direkte Änderungen wirken sich sofort auf die Vorschau aus.
Fehlerbehandlung: Fallback für Worker-Skript beim GIF-Export, um lokale Datei-Probleme zu vermeiden.
