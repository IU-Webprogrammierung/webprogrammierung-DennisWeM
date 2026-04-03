# Persönlicher Webauftritt von Dennis Weigand-Müller

## Projektbeschreibung
Dieses Projekt zeigt einen persönlichen Webauftritt, der meine Hobbys Theater spielen und Musik sowie weitere Informationen vorstellt. Die Website wurde mithilfe von HTML und CSS umgesetzt. Der Fokus lag auf einer klaren Struktur, responsives Verhalten und grundlegende Barrierefreiheit.

## Seitenübersicht
Die Website besteht aus folgenden Seiten:

- Startseite
	- Einstieg zum Webauftritt
	- Kurze Vorstellung
	- Kleiner Teaser zu den Bereichen Theater und Musik

- Theaterseite
	- Überblick über die vorhandene Theatererfahrung
	- Stücke und Rollen
	- Bilder mit Unterschriften

- Musikseite
	- musikalische Erfahrungen und Projekte
	- Projektbeschreibung mit Bildern und Unterschriften

- Über-mich-Seite
	- Persönliche Informationen
	- Kurzprofil
	- Kontaktbereich mit Formular
	- Impressum und Datenschutzbereich

- 404-Seite
	- eigene Fehlerseite für nicht vorhandene Inhalte

## Verwendete Technologien

- HTML5
- CSS
- Flexbox
- Media Queries
- CSS Variablen
- Git
Auf die Nutzung von CSS-Frameworks oder Javascript wurde verzichtet.


## Responsive Design
Die Website wurde responsiv umgesetzt. Sie bietet eine fehlerfreie Darstellung über die gesamte Breite von 360px bis 1920px.Sie besitzt einen Breakpoint bei 768px.

- Desktopansicht:
	- Inhalte wie Texte und Bilder werden grundsätzlich nebeneinander dargestellt. Die Navigation wird ebenfalls nebeneinander 	angeordnet. 
- Mobile Ansicht:
	- Inhalte werden untereinander angeordnet. Die Navigation wird ebenfalls untereinander angeordnet.

## Layout und Gestaltung
Für das Layout wurde hauptsächlich flexbox verwendet.

-Einsatzbereiche:
	- Header mit Logo und Navigation
	- Teaserbereich auf der Startseite
	- Artikel auf der Theater -und Musikseite
	- Übersichtsbereiche

Zusätzlich wurden folgende Gestaltungsmerkmale umgesetzt:
	- Einheitliche Farbgestaltung über CSS-Variablen
	- Kartenförmige Inhaltsbereiche
	- Responsive Bilder
	- Hover-Effekte für Bilder
	- Back-to-top-Link
	- Favicon
	- Dark Mode mithilfe von prefers-color-scheme

## Barrierefreiheit
Folgende Maßnahmen zur Barrierefreiheit wurden berücksichtigt:

	- Semantische HTML-Struktur mit Header, nav, main, section, article, figure, figcaption, address, form
	- Skip-Link zum direkten Springen zum Hauptinhalt
	- Kennzeichnung der aktiven Seite in der Navigation mit aria-current-page
	- aria-label für die Hauptnavigation
	- Alternativtexte für Bilder
	- Klare Überschriftenstruktur
	- Responsive Darstellung für unterschiedliche Bildschirmgrößen

## Formular
Auf der Über-mich-Seite wurde eine Kontaktformular eingebunden.

Enthaltene Felder:
	- Name
	- Email
	- Nachricht

Zusätzlich wurde eine HTML-Validierung verwendet, mit z.B:
	- "required"
	- "minLength"
	- type = "email"

## Erweiterungen

Über die Grundanforderungen hinaus wurden folgende zusätzlichen Elemente umgesetzt:

	- eigene 404-Seite
	- Back-to-Top-Link
	- Dark Mode
	- Kontaktformular
	- Favicon
	- Hover-Animationen für Bilder
	- Impressum und Datenschutzfelder

# Git-Workflow
Das Projekt wurde mit Git versioniert und über Github verwaltet. Während der Bearbeitung wurden regelmäßig Commits erstellt, um die Entwicklungschritte nachvollziehbar zu dokumentieren. Insgesamt wurden schrittweise 100 Commits erstellt.

## Erkenntnisse aus dem Projekt
Im Verlauf des Projekts wurden insbesondere Inhalte praktisch angewendet und vertieft:

	- Aufbau semantischer HTML-Strukturen
	- Einsatz von Flexbox für Layouts
	- Umsetzung responsiver Seiten mit Media Queries
	- Responsive Bilddarstellung
	- Grundlegende Barrierefreiheit
	- Anwenden von CSS-Variablen
	- Arbeiten mit Git und Github
	- Debugging mit Entwicklerwerkzeugen, z.B. Inspektor im Browser
	- Bearbeitung von Medien hinsichtlich Webperformance, z.B. komprimieren von Bildgrößen von 16mb auf < 300 kb
	- Schrittweise Entwicklung über mehrere Phasen

## Fazit
Das Projekt zeigt die Entwicklung eines vollständigen persönlichen Webauftritts mit HTML und CSS, welcher über mehrere Phasen hinweg entwickelt wurde. Im Mittelpunkt standen sinnvolle Inhalte, eine klare Struktur, Barrierefreiheit, responsives Verhalten sowie die Nachvollziehbarkeit der technischen Umsetzung.

	