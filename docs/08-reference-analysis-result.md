# Referenzanalyse Preymaker / Ownitt → Richtungen für flaetchen

Stand: 2026-10-09 · Ergebnis von `00-start-prompt.md` · Keine Entscheidung, keine Implementierung

Grundlage: Beide Startseiten wurden live analysiert, mit DOM-Struktur, Schriften, Medien, Scroll-Mechanik und Screenshots je Szene.

---

## 1. Preymaker — Analyse

**Technik-Befund**
- Eine Schrift (NewGrotesk), Lenis-Smooth-Scroll, eigener Cursor.
- 19 Videos auf der Startseite (1080p-Previews vom CDN), davon spielt immer nur das aktive.
- Keine WebGL-Bühne.

| Punkt | Mechanik |
|---|---|
| Visuelle Hierarchie | Bewegtbild vor Schrift. Medien sind immer vollflächig, Text ist klein und sitzt auf dem Bild. Die H1 ist nur ca. 28 px groß (Semibold). |
| Hero | Preloader (Vogel-Marke, „Loading… 100 %“ auf Hellgrau), dann Schwarz mit Markenfilm (Flügel-Loop). Die zweizeilige Headline steht klein rechts von der Mitte, unten ein kleines „Scroll Down“. |
| Typografie | Eine Grotesk, fast nur klein: 12–28 px, Versalien-Labels, Projektnamen fett in Versalien. Groß ist nur das Bild. Links sind pro Buchstabe zerlegt für Roll-Hovers. |
| Navigation | Winzige Kopfzeile (Logo links, MENU mittig, SEARCH rechts), verschwindet beim Scrollen. Overlay-Menü mit Spalten Pages / Explore / Socials plus Suche. |
| Projekte | Ein „Sticky“-Abschnitt mit 7 Projekt-Kapiteln. Jedes ist ein vollflächiges Video. Das nächste schiebt sich per `clip-path`-Wipe von unten über das aktuelle. Name und Kunde stehen dabei **fest in der Bildmitte**, Leistungen klein rechts. Danach ein 12-Spalten-Raster aus Video-Kacheln mit „See more work (208)“ in der Mitte. |
| Bild / Video | Ausschließlich Bewegtbild der eigenen Arbeit (VFX, Werbefilme). Kein Stock, keine Mockups. |
| Pacing | Preloader → Markenfilm → 7 Kino-Kapitel → dichtes Raster → ein Absatz Positionierung → Partnerliste (21 Namen als Text, „See all 269“) → News → Schlusssatz → Footer „Next page: Work“ |
| Motion | Bewegung steckt fast nur im Medium. Projektwechsel per Wipe, Text bleibt stehen, kleine Buchstaben-Rolls beim Hover. |
| Szenenwechsel | Wipe von unten. Am Seitenende zieht „Next page“ in die nächste Seite. |
| Weißraum | Kaum klassischer Weißraum. Schwarz und kleine Schrift erzeugen die Leere. |
| Was es premium macht | Die Gelassenheit kleiner Schrift vor riesigem Bild. Beweis durch Menge (208 Arbeiten, 269 Partner). Nur Schwarz und Weiß. |
| Was hängen bleibt | Der Kino-Stapel: Bild wechselt, Titel bleibt stehen. |
| Passt zu flaetchen | Arbeit zuerst. Vollflächige Projekt-Kapitel mit festem Titelanker. Schwarz als Bühne. Kuratierte Auswahl, danach der Index. Nur ein aktives Video. „Nächste Seite“ als Abschluss. |
| Passt nicht | Das Material: Preymaker hat Filme, flaetchen hat Websites und Marken. Sehr kleine Typo widerspricht euren großen Headlines. Preloader. Eigener Cursor. Logo-Wand. |
| Strukturprinzip statt Oberfläche | (a) Medium ist der Held, Schrift sitzt darauf. (b) Fester Textanker, während das Bild wechselt. (c) Erst kuratierte Kapitel, dann ein Index von allem. (d) Immer nur ein aktives Medium. |

## 2. Ownitt — Analyse

**Technik-Befund**
- Zwei Schriften (elza-condensed, ivypresto-display), Lenis-Smooth-Scroll.
- 7 Videos, Seite ca. 27.000 px lang, Grün als Akzent.

| Punkt | Mechanik |
|---|---|
| Visuelle Hierarchie | Worte vor Bildern. Statements dominieren. Bilder sind inszenierte Schwarzweiß-Fotografie, nicht die Arbeit selbst. |
| Hero | Intro-Loader: Die Wortmarke füllt sich aus der Kontur, „Agence créative“ in kursiver Serif, „Passer“ zum Überspringen. Danach heller Cremegrund mit Logo, Stern-Zeichen und rotierender Ortsliste (Pays Basque, Landes, Bordeaux, Paris). |
| Typografie | Kontrast aus schmaler, fetter Grotesk in Versalien und kursiver Display-Serif für Nuancen. Dieser Wechsel ist die Stimme. Im Manifest färbt sich der Text Wort für Wort beim Scrollen von dunkel zu hell. |
| Navigation | Runder MENU-Button. Jeder Menüpunkt hat eine Haltungszeile („Réalisations – Le travail, sans filtre“). Seitliches „W.“-Award-Badge. |
| Projekte | Gepinnte Folge von 8 Cases. Jeder Case ist ein Vollbild-Panel mit eigener Grundtönung. Links: Kunde, Leistungen, Titel in kursiver Serif, **ein Satz als Aufhänger** („Et si votre visage suffisait à commander ?“), „Voir le projet“. Rechts das Mockup, dazu eine riesige Nummer und ein seitlicher Index 01–08. |
| Bild / Video | Showreel im gerahmten Player (Ton / Vollbild). Schwarzweiß-Porträts von Models mit Haltung. Die Wortmarke als Bildmaske mit Fotos in den Buchstaben. |
| Pacing | Statement → SEO-Absatz (Positionierung + Ort) → Showreel → Manifest (3 Viewports) → Wörterbuch-Definition „ownitt \ow·nit\ verbe“ → Wortmarke mit Foto → Versprechen → 8 Cases → „Et ce n'est qu'un aperçu“ → „Et concrètement…“ → 5 Leistungsfelder → „Toujours pas convaincu ?“ → Newsletter |
| Motion | Wort-für-Wort-Färbung, Masken-Reveals, gepinnter Case-Stapel, Laufband beim Hover über Leistungen |
| Szenenwechsel | Wechsel zwischen Hell und Dunkel, Pin-Stapel |
| Weißraum | Großzügig um die Statements |
| Was es premium macht | Die Stimme. Durchgehend art-direktierte Fotografie. Rhetorische Fragen als Kapitelverbinder („Mais qu'est-ce qu'on fait, exactement ?“). |
| Was hängen bleibt | Manifest und die Definition des eigenen Namens |
| Passt zu flaetchen | Haltung und Stimme („Vollblut“ trägt das). Fragen als Kapitelverbinder. SEO-Absatz elegant integriert. Leistungen als große Wortliste mit Tiefe. Menüpunkte mit Haltungszeile. Ein Aufhänger-Satz pro Case. |
| Passt nicht | Serif + Condensed (bei euch nur Outfit), Cremegrund, **grüner Akzent zu nah an #bcff03**, Wortmarke als Bildmaske, gestellte Model-Fotografie, Award-Badge, Länge der Seite, Intro-Loader |
| Strukturprinzip statt Oberfläche | (a) Die Stimme führt durch Kapitel, Fragen verbinden sie. (b) Das Manifest ist eine eigene Szene. (c) Jeder Case hat einen Aufhänger-Satz. (d) Leistungen sind Wörter, keine Karten. |

> **Konsequenz:** Die Idee „Arbeit durch die Buchstaben sehen“ aus meinen früheren Entwürfen macht Ownitt bereits mit der eigenen Wortmarke. Sie ist damit für flaetchen verbrannt und gestrichen.

## 3. Gemeinsame Prinzipien

- Schwarz als Bühne, eine reduzierte Palette, ein Akzent
- Ein Gedanke pro Viewport
- Kuratierte Cases als gepinnte Folge, jeweils vollflächig
- Kleine Kopfzeile plus Vollbild-Menü
- Beweis statt Behauptung (Zahlen, Kundennamen, echte Arbeit)
- Der Seitenabschluss führt weiter, statt zu enden

## 4. Widersprüche

| Preymaker | Ownitt |
|---|---|
| Das Bild spricht, Schrift ist klein | Worte sprechen, Schrift ist groß |
| Kühl, still | Laut, mit Stimme |
| Kurz, verdichtet | Lang, erzählend |
| Nur eigene Arbeit als Bild | Inszenierte Fotografie als Bild |

**Auflösung für flaetchen:** Den Widerspruch als Rhythmus nutzen.
- **Ruhige Szenen gehören der Sprache:** große Outfit-Statements mit Gewichtskontrast, die Ownitt-Seite.
- **Arbeits-Szenen gehören dem Bild:** Die Schrift tritt zurück, die Preymaker-Seite.
- Ruhig, stark, ruhig, stark, genau wie in `01-creative-direction.md` gefordert.

## 5. Was zu flaetchen passt

- Projekt-Kapitel vollflächig mit festem Textanker (Preymaker)
- Erst die Kuration, dann der vollständige Index mit Anzahl (Preymaker)
- „Nächste Seite“ als Abschluss jeder Seite und jedes Cases (Preymaker)
- Stimme und Haltung, Fragen als Kapitelverbinder (Ownitt), auf Deutsch, aus „Vollblut“ heraus
- Ein Aufhänger-Satz pro Case (Ownitt)
- Leistungen als große Wörter, keine Karten (Ownitt)
- Menüpunkte mit Haltungszeile (Ownitt)
- Ein Positionierungsabsatz mit Ort für die Suche (Ownitt)

## 6. Was nicht passt

- Preloader und Intro-Loader (kosten LCP, wirken nach Template)
- Eigener Cursor, Smooth-Scroll als Standard (laut CLAUDE.md nicht standardmäßig)
- Zweite Schrift, Serif-Kursive, Cremegrund
- Grün-Akzent-Nähe: Neon bei flaetchen muss anders eingesetzt werden als Ownitts Grün, nämlich seltener und nie als Satzzeichen-Gag
- Wortmarke als Bildmaske
- Gestellte Model-Fotografie, Award-Badges, Logo-Wände
- Sehr kleine Typo als Grundhaltung

**Das Kernproblem des Materials:** flaetchen zeigt Websites und Marken, keine Filme. Wer Preymakers Kino-Prinzip übernimmt, muss Bildschirm-Arbeit filmisch machen: Scroll-Fahrten durch echte Seiten als Video, Marken-Details im Anschnitt, mobile Ansichten im Hochformat. Flache Screenshots tragen das nicht.

**Farbe:** Die Projekte haben völlig verschiedene Farbwelten (Joshua Navy, smenso Pink-Violett, Eukora Gold). Jeder Projektwechsel braucht deshalb eine Lösung, siehe offene Entscheidungen.

## 7. Vorschlag Startseiten-Dramaturgie

1. **Haltung (ruhig):** Statement in Outfit mit Gewichtskontrast plus klarer Satz, wer flaetchen ist und wo.
2. **Arbeit (stark):** 4–5 kuratierte Cases als vollflächige Kapitel mit festem Titelanker und Aufhänger-Satz.
3. **Index (ruhig):** „Und das ist ein Ausschnitt.“ Alle Projekte als typografische Liste mit Anzahl.
4. **Kompetenz (Kapitel):** Branding, Digital Design, Development, Strategie. Jedes Kapitel mit einem Satz Haltung, Klartext-Leistungen und einem Beleg aus der Arbeit.
5. **Person (persönlich):** Sven, redaktionell, ein Absatz in der ersten Person.
6. **Abschluss (stark):** Kontakt groß, danach „Nächste Seite: Arbeiten“.

## 8. Drei Hero-Richtungen

| | Was man sieht | Stärke | Risiko |
|---|---|---|---|
| **H1 · Statement** | Schwarz. Eine Headline füllt die Breite, z. B. „**Vollblut**marketing & **Design.**“ mit Gewichtskontrast. Darunter ein Sachsatz. Kein Bild. Der erste Scroll schiebt das erste Projekt per Wipe darüber. | Schnellster LCP, maximal markeneigen, ruhig vor dem Sturm | Ohne Bild weniger Sog in der ersten Sekunde |
| **H2 · Werkschau-Film** | Vollflächiger Loop aus geschnittenen Arbeiten (Scroll-Fahrten, Marken-Details), die Schrift sitzt klein bis mittel darauf | Arbeit ab der ersten Sekunde, kinoartig | Braucht einen echten Schnitt (Produktion), Gefahr „Showreel-Agentur“ |
| **H3 · Person zuerst** | Svens Porträt groß und redaktionell, daneben das Statement. Die Arbeit folgt direkt danach. | Stärkste persönliche Präsenz, unverwechselbar | Kippt schnell ins Eitle, hängt komplett an der Fotoqualität |

## 9. Drei Richtungen für die Projektpräsentation

| | Mechanik | Stärke | Risiko |
|---|---|---|---|
| **P1 · Kinostapel** | Vollflächige Kapitel, das nächste Projekt wischt von unten über das aktuelle. Name, Kunde und Aufhänger stehen fest, Leistungen klein am Rand. Nur das aktive Video läuft. | Bewährt kraftvoll, ruhig, klar | Am nächsten an Preymaker, braucht starkes Bewegtbild |
| **P2 · Fallakte** | Pro Case ein Viewport: links Text (Kunde, Leistungen, Aufhänger), rechts großes Medium, Index am Rand. Farben der Projekte in Grautöne übersetzt. | Viel Information, sehr gut für SEO, ruhig | Weniger spektakulär, nah an Ownitt |
| **P3 · Bildschirm-Fahrt** | Jedes Projekt ist eine rahmenlose Fläche, in der die echte Website scrollgekoppelt durchläuft. Der Name steht groß daneben. Der Wechsel zum nächsten Projekt geht durch Schwarz. | Am spezifischsten für eine Web-Agentur: Die Arbeit wird benutzt, nicht gezeigt | Braucht saubere Full-Page-Aufnahmen pro Projekt |

## 10. Kompetenz-Storytelling

- Vier Kapitel, jedes in voller Viewport-Höhe.
- **Pro Kapitel:**
  - Disziplin sehr groß in Outfit
  - ein Satz Haltung
  - 4–5 Leistungen in Klartext
  - ein Projekt als Beleg
  - Link zur Leistungsseite
- **Verbinder:** Wie bei Ownitt führen Fragen in eigener deutscher Stimme durch, z. B. „Und was heißt das konkret?“ Keine Karten, keine Icons.

## 11. Gründer und Porträt

- **Option A:** Ruhige redaktionelle Szene mit großem Porträt und einem Absatz in der ersten Person
- **Option B:** Ein Zitat von Sven als Zwischenszene im Arbeitsfluss
- **Option C:** Porträt zusätzlich im Menü neben „Sven Flaetchen“

**Material:** Der vorhandene Freisteller (Studio, ohne Umgebung) wirkt eher nach Katalog. Für ein Premium-Niveau wäre ein redaktionelles Foto mit Umgebung und Licht stärker. Das ist eine Entscheidung über neue Assets.

## 12. Vollbild-Menü

- Schwarz, Einträge groß in Outfit, jeder mit einer Haltungszeile darunter.
- Rechts das aktuelle Projekt als laufendes Medium, darunter Kontakt.
- Neon nur am aktiven Eintrag.
- Öffnen per Wipe von oben, Einträge gestaffelt.
- Echter Dialog: Fokus-Falle, Esc schließt, Hintergrund `inert`.

## 13. Bewegungssprache

- **Medien bewegen sich, Schrift steht.**
- **Projektwechsel:** per Masken-Wipe.
- **Statements:** Wenn überhaupt, ändert sich beim Lesen das Gewicht, nicht die Farbe. Das grenzt von Ownitts Wort-Färbung ab.
- **Keine Dauerbewegung,** kein Federn.
- **Ein gemeinsames Easing** für alle Szenenwechsel.

## 14. Seitenübergänge

- Vom Teaser zum Case bleibt das aktive Medium stehen und wird zum Case-Hero, nur der Text wechselt (Shared Element / View Transitions).
- Am Ende jedes Cases steht „Nächstes Projekt“ vollflächig, der Scroll zieht hinein.
- Zwischen normalen Seiten ein kurzer, ruhiger Wipe.

## 15. Mobil

- Keine Pins, die Kapitel stehen untereinander in voller Höhe.
- Medien im Hochformat: mobile Ansichten der Websites, die genau dafür ideal sind.
- Das Menü bleibt gleich.

## 16. SEO / GEO

- **Startseite:** ein klarer Positionierungsabsatz (Agentur für …, Sitz St. Ingbert, Saarland).
- **Cases:** Fakten als Text (Kunde, Leistungen, Ergebnis).
- **Leistungen:** eigene Seiten.
- **Strukturierte Daten:** `Organization` / `LocalBusiness` für die regionale Suche, `CreativeWork` pro Case.
- Keine Inhalte nur im Video.

## 17. Barrierefreiheit

- **Videos:** Länger als 5 Sekunden laufende Videos brauchen eine Pause-Möglichkeit.
- **Kontrast:** Text auf Video bekommt ausreichend Kontrast (Abdunklung).
- **Reduzierte Bewegung:** Poster statt Video, keine Wipes.
- **Menü:** echter Dialog, sichtbarer Fokus.

## 18. Performance

- Preymaker lädt 19 Videos auf der Startseite. flaetchen lädt nur das aktive Medium, der Rest bekommt Poster und `preload="none"`.
- Videos in 720p/1080p (H.264 + AV1), Poster als AVIF.
- Kein Preloader. LCP ist die Headline oder das erste Poster.

## 19. Offene Entscheidungen

1. Hero-Richtung: H1, H2 oder H3
2. Projektpräsentation: P1, P2 oder P3
3. Farbe der Projekte beim Wechsel:
   - (a) volle Farbe, Wechsel durch Schwarz
   - (b) Grautöne während der Bewegung, Farbe erst beim Halt
   - (c) volle Farbe ohne Zwischenschritt
4. Bewegtbild-Material: Sollen Scroll-Fahrten und Detail-Clips der Projekte produziert werden? Welche Projekte, welche Reihenfolge?
5. Gründer: Option A, B oder C, und ob ein neues redaktionelles Foto entsteht
6. Stimme: Wie direkt darf „Vollblut“ klingen, Ownitt-laut oder ruhiger?
7. Haltungszeilen im Menü: ja oder nein
8. Smooth-Scroll: Beide Referenzen nutzen Lenis, CLAUDE.md sagt standardmäßig nein. Später prüfen?
9. Sprache: nur Deutsch?
