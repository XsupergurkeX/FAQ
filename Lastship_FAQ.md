# Lastship für Kodi -Deutsche Anleitung/ FAQ


![Lastship Logo](https://raw.githubusercontent.com/lastship/FAQ/master/Lastship_Logo1.png)


- [1. Allgemeines zum Addon](#1-allgemeines-zum-addon)
    - [1.1 Verfügbare Webseiten](#11-verfügbare-webseiten)
    - [1.2 Rechtliche Konsequenzen bei Nutzung](#12-rechtliche-konsequenzen-bei-nutzung)
   
   
- [2. Installation und Konfiguration](#2-installation-und-konfiguration)
    - [2.1 Bezugsquellen zur Installation](#21-bezugsquellen-zur-installation)
    - [2.2 Allgemeine Einstellungen und Wiedergabe](#22-allgemeine-einstellungen-und-wiedergabe)
    - [2.3 Index Seiten Aktivieren und Deaktivieren](#23-index-seiten-aktivieren-und-deaktivieren)
    - [2.4 Hosterwahl](#24-hosterwahl)
    - [2.5 Konten](#25-konten)
    - [2.6 Untertitel](#26-untertitel)
    - [2.7 Downloads](#27-downloads)
    - [2.8 URL Resolver Konfiguration](#28-url-resolver-konfiguration)
    - [2.9 Trakt](#29-trakt)
    - [2.10 Gemeinsamer gesehen Status in Lastship und xStream](#210-gemeinsamer-gesehen-status-in-lastship-und-xstream)
    - [2.11 Lastship Bibliothek](#211-lastship-bibliothek)
    - [2.12 Sortierung der gefundenen Links in der Ergebnisliste](#212-sortierung-der-gefundenen-links-in-der-ergebnisliste)
 
- [3. Bekannte Probleme](#3-bekannte-probleme)
    - [3.1 Fehler bei der Installation](#31-fehler-bei-der-installation)
    - [3.2 URL Resolver Fehler](#32-url-resolver-fehler)
    - [3.3 Beobachtungen und Fehler im Betrieb](#33-beobachtungen-und-fehler-im-betrieb)
  
- [4. Fehlerbericht über Log-Datei](#4-fehlerbericht-über-log-datei)
    - [4.1 Allgemeines zur Log-Datei](#41-allgemeines-zur-log-datei)
    - [4.2 Speicherort der Log Datei](#42-speicherort-der-log-datei)
    - [4.3 Erstellen und Hochladen der Log-Datei](#43-erstellen-und-hochladen-der-log-datei)

    
- [5. Phyton Dateien](#5-phyton-dateien)
    - [5.1 Allgemeines zur .py-Datei](#51-allgemeines-zur-py-datei)
    - [5.2 Bearbeiten einer .py-Datei](#52-bearbeiten-einer-py-datei)
    - [5.3 Speicherort der einzelnen Webseiten (.py Dateien)](#53-speicherort-der-einzelnen-webseiten-py-dateien)



# 1. Allgemeines zum Addon

Wir suchen Entwickler!!

Dies Anleitung bezieht sich auf das Addon Lastship

Lastship ist, genau wie xStream,  ein Video Addon für die Media-Center-Software Kodi

Mit Lastship ist es möglich über eine einfache Benutzeroberfläche mehrere Streaming-Seiten zu benutzen, mit denen man Filme und Serien anschauen kann.

Dabei greift Lastship bei Film/Serienauswahl oder einer Suche zuerst auf eine Filmdatenbank zu (z.B.imdb, tvdb)zu und zeigt ein Ergebnis an

Erst nach der getroffenen Auswahl werden die Anbieter & Hoster durchsucht

Der Menüaufbau von Lastship ist eigentlich selbsterklärend

Die Menüsprache von Lastship ist jene Sprache, auf die Kodi eingestellt ist

Unterstützung und Anfragen zu den Deutschen Seiten, Problemen usw. werden über das Lastship Forum abgewickelt

Einstellungen welche in Lastship gemacht werden, sind in einer sogenannten settings.xml gespeichert

Diese kann von einem System auf ein anderes kopiert werden um auch dort die gleichen Einstellungen (Konten usw,) zu haben

Die settings.xml von Lastship findet man hier:

....kodi/userdata/addon_data/plugin.video.lastship

Der .kodi Ordner ist ein versteckter Ordner und muss in Windows  und Android erst sichtbar gemacht werden

Weiter Pfade stehen im Kap. 4.2

## 1.1 Verfügbare Webseiten

Die Funktion der folgenden Seiten ist auf Grund Fehlender Entwickler nicht gewährleistet

| Name           | Domain            | Hinzugefügt        |
|:-------------- |:----------------- | :------------------|
|		 |		     |		  |
|Amazon  	 |amazon.de  	     | 14.06.2018 |
|Animebase	 |anime-base.net     | 07.05.2017 |
|Animeloads      |anime-loads.org    | 23.02.2017 |
|Cinematrix      |cinematrix.to      | 15.07.2018 |
|Cinemaxx        |cinemaxx.cc	     | 27.06.2918 |
|DirectDownLoad  |ddl.me             | 12.01.2017 |
|FilmPalast      |filmpalast.to      | 12.01.2017 |
|Foxx            |foxx.to            | 24.08.2017 | 
|HDfilme         |hdfilme.tv         | 12.01.2017 |
|HDKino	         |hdkino.to	     | 18.06.2018 |
|HDStreams	 |hd-streams.org     | 14.06.2017 |
|Horrorkino      |horrorkino.do.am   | 02.06.2017 |
|iLoad           |iload.to           | 12.01.2017 |
|KinoDogs        |kinodogs.to        | 28.01.2017 |
|Kinoger         |kinoger.com	     | 21.03.2018 |
|Kinoking        |kinoking.to        | 30.08.2017 |
|Kinow           |kinow.to           | 23.05.2017 |
|KinoX           |kinox.to           | 12.01.2017 |  
|Moovie	         |securelink	     | 04.05.2018 |
|Movie-gg        |movies.gg	     | 04.05.2018 |
|Movie2k         |movie2k.sc/ag      | 01.09.2017 |
|Movie4k-lt      |movie4k.lt	     | 08.06.2018 |
|Movie4k         |movie4k.to         | 13.02.2017 |
|MovieTown       |movietown.org      | 30.08.2017 |
|Netzkino        |netzkino.de        | 16.04.2017 |  
|Proxer		 |proxer.me          | 14.07.2017 |
|Serienstream	 |serienstream.to    | 08.01.2018 |
|Streamdream     |streamdream.ws     | 09.03.2018 |
|Streamit        |streamit.ws        | 17.03.2017 |
|Szene-streamz   |szene-streamz.com  | 14.03.2018 |
|Tata	         |tata.to	     | 20.01.2018 |
|View4u 	 |view4u.co   	     | 14.07.2017 |
|VodHD	         |vodhd.to	     | 04.05.2018 |


Für die Verwendung von Serienstream.to, ist auf deren Homepage das Anlegen eines Benutzer Kontos erforderlich.

Als E-Mailadresse kann auch eine Wegwerf-EMail-Adresse verwendet werden

Die Seite VodHD ist Standardmäßig deaktiviert, da diese Seite eine Premium Seite ist, dass heißt es muss für die Nutzung bezahlt werden. Infos zu Bezahlung und Anmeldung auf https://vodhd.to/

Diese Daten dann bitte in Lastship unter: Werkzeuge - Konten eingeben, ab da kann Serienstream genutzt werden

 
Für die Verwendung von foxx.to muss zusätzlich das script.module.request installiert sein/werden (wird normalerweise bei der Installation mit installiert)

Für die Verwendung von Amazon siehe Kaiptel 2.3 Index Seiten

Empfehlungen und Vorschläge für neue Seiten können über das Lastship Forum gemacht werden

Die Intergration der eingereichten Seiten ist nicht selbsverständlich und folgt daraufhin auch nicht automatisch. 

Sowohl das Potenzial der vorgeschlagenen Seite als auch der erforderliche Mehrwert wird geprüft und entscheidet über die Entwicklung eines neuen Site-Plugins.

Grundsätzlich ist jedoch zu erwähnen, dass stätig an der Weiterentwicklung von Lastship und deren Site-Plugins gearbeitet wird.


## 1.2 Rechtliche Konsequenzen bei Nutzung

Der Europäische Gerichtshof hat ein Urteil gefällt: 
 
 - Der Nutzer muss sich in Anbetracht des neuen EuGH-Urteils stets über das zur Nutzung vorgesehene Angebot (Portal, Webseite) informieren – der Nutzer muss prüfen, ob das Angebot rechtswidrig ist oder sein könnte. 

 - Streamingseiten, die etwa brandaktuelle Kinofilme kostenlos anbieten, die man nicht mal bei den Bezahlanbietern zu sehen bekommt – hier hat man es wahrscheinlich mit einer „offensichtlich rechtswidrigen Vorlage“ zu tun. 
 
Wer sich hier Streams anschaut, macht sich strafbar und kann sich nicht auf das Recht auf Privatkopie berufen.

 - Zukünftige Streaming-Abmahnungen sind also durchaus möglich,eine neue Abmahnwelle ist dennoch nicht zu befürchten
Nutzer können nur über ihre IP-Adressen zurückverfolgt werden Genau diese IP-Adresse ist jedoch nur dem illegalen Portal bekannt, welches meist anonym operiert und oft keine IP-Adressen speichert

Die meisten Streaming-Seiten speichern keine Zugriffsdaten

Solltet Ihr einen Premium Dienst auf diversen Seiten nutzen, könnt Ihr natürlich leicht(er) gefunden werden

Hier ist ein Video von Rechtsanwalt Christian Solmecke, der über das Thema rechtlich aufklärt: Stand 26.April 2017


[![EuGH: Streaming| Rechtsanwalt Christian Solmecke](https://i.ytimg.com/vi/uzOA09gomn0/hqdefault.jpg)](https://www.youtube.com/watch?v=uzOA09gomn0&feature=youtu.be)

[Link](https://www.youtube.com/watch?v=uzOA09gomn0&feature=youtu.be)

# 2. Installation und Konfiguration

## 2.1 Bezugsquellen zur Installation

**Das hinzufügen von Lastship über "als Quelle hinzufügen" in Kodi ist NICHT möglich!!!**

[Info] Das (Deutsche)Lastship Project sucht Entwickler  zur Pflege der Index Seiten, Kenntnisse Programmiersprache Python (.py) erforderlich

Das Video Addon Lastship  wird über das  LASTSHIP Repository installiert 

Dieses ist hier verfügbar: [Download](https://github.com/lastship/Lastship-Repo/blob/master/zips/repository.lastship/repository.lastship-1.0.2.zip)

Forum: [Link](http://www.lastship.square7.ch/home/forum/index.php?thread/58-download-lastship-repository/#post128)
 
Die Entwicklung und Änderungen in Lastship können auf Github mitverfolgt werden, der Download sollte jedoch vom Downloadlink oben durchgeführt werden: [Lastship auf Github](https://github.com/lastship?tab=repositories)

Die Aktualisierung von Lastship erfolgt NUR über das Lastship Repository, so wie bei jedem anderen Repo auch

Nach einem Update, werden dann auch neu hinzugefügte Index-Seiten automatisch angezeigt

Wollt Ihr nicht bis zu einem Update warten, könnt Ihr die aktuellen Daten aus der Lastship -nightly Version downloaden und in das entsprechende Verzeichnis kopieren: 

[plugin.video.lastship](https://github.com/lastship/plugin.video.lastship/tree/nightly)

**BEACHTE:**

*Beim gesamten Daten Download von Github* gilt es folgendes zu Beachten:

Um eine Korrekte Installation zu Gewährleisten, ist es immer notwendig, den Anhang Master, Beta, Nightly aus den .zip Dateien und dem Unterordner zu entfernen

*Geht wie folgt:*

Die Datei in “plugin.video.lastship-master.zip” umbenennen (quasi das “-master" entfernen)

Dann Datei öffnen (nicht entpacken) mit 7-Zip, WinRAR, WinZIP (oder einem anderen Packer), dort ist ein Ordner zu sehen der z.B. “plugin.video.exodus-master” heißt => auch hier das “-master” entfernen

Die Zip dann installieren.
 
Im Lastship Repo ist auch das lastship-common repo enthalten

Dadurch aktualisiert sich auch der URL Resolver, wenn es ein URL Resolver Repo-Update gibt

**Es wird Jsergio als Quelle für den URLResolver verwendet**

Von dort beziehen auch wir die Informationen und aktualisieren, den URLResolver welcher im Repo liegt, selbst

Aktueller URL Resolver: [Link](https://github.com/lastship/lastship-common/tree/master/zips/script.module.urlresolver)

Lastship und xStream verwenden  den gleichen metahandler

***Hinweis:*** 

An dieser Stelle muss darauf hingewiesen werden, dass unter alternativen Bezugsquellen nicht für den aktuellsten Stand und Funktion der Software garantiert werden kann!

Repo Installieren:

- öffne die Kategorie Addons

- aus zip installieren

- Downloadordner suchen und installieren

Nach dem das Repo Installiert wurde ist noch folgendes zu machen:

- öffnet die Kategorie Addons

- Aus Repository installieren

- Lastship Repository

- *Video-Addons*

- Lastship (installieren/aktivieren)

## 2.2 Allgemeine Einstellungen und Wiedergabe

Wenn gesehene Filme auf einmal weg sind, liegt das an den Einstellungen im Seitenmenü. 

Hier die Markierung „gesehene Filme“ deaktivieren!

In Lastship  Kategorie *WERKZEUGE* öffnen

Hier werden alle Lastship Einstellungen angezeigt

**LASTSHIP: Index Seiten Cache (Speicher) löschen**

Löscht den Index Seiten Cache (Speicher) von Lastship

Das ist jener Speicher, wo gesuchte bzw. besuchte Index Seiten gespeichert werden, damit diese beim nächsten mal schneller geladen werden

Keine Angst, hierbei passiert nichts!!

**LASTSHIP: Suchverlauf löschen**

Hierbei wird der gesamte Suchverlauf, bei Serien, Filme, Crew usw. gelöscht

**LASTSHIP: Cache (Speicher) leeren**

Löscht den Cache (Speicher) von Lastship, ist wie bei jedem Internet Browser

Keine Angst, hierbei passiert nichts!!

**LASTSHIP: Metadaten Speicher löschen**

In diesem Cache (Speicher) werden Informationen zu Filmen/Serien (Covers, TMDb bzw. IMDB Links, Beschreibungen usw.) gespeichert

Das ermöglicht einen schnelelrn Abruf der Informationen

Beim löschen des Metadaten Speicher werden diese Infos gelöscht

Keine Angst, hierbei passiert nichts!!

**LASTSHIP: Lösche alle Speicher**

Hier werden ALLE Caches (Speicher) gelöscht (Metadaten, Index Seiten und Lastship Cache)

Keine Angst, hierbei passiert nichts!!

**Suche**

Die Suche in Lastship ist eine Globale Suche

Das heißt, es werden immer alle Anbieter/Hoster durchsucht

Wird ein Ergebnis angezeigt, so bedeutet das noch nicht, dass auch ein Stream vorhanden ist (denn Lastship durchsucht eine Datenbank)

Wird kein Ergebnis gefunden, so wird die Suche beendet und "Nichts gefunden" angezeigt

Es kann vorkommen, dass eine Serie/ein Film nicht gefunden wird, näheres dazu siehe Kapitel 3.3

Auf die Kategorien *Meine TV Serien* und *Meine Filme* hat man nur Zugriff mit einem Trakt.tv Konto (siehe in den entsprechenden Kapiteln)

**LASTSHIP: Anzeige Typen**

Hier wird die Ansicht (view) eingestellt, wie Filme/Serien/Episoden usw. dargestellt werden (Liste, Wall, InfoWall, Poster usw...)

Diese Ansichten werden in einer eigenen Datenbank gespeichert:

.....kodi\userdata\addon_data\plugin.video.lastship\views.db

Und so stellt Ihr die Ansichten ein:

Lastship Menü -> Werkzeuge ->Angezeigte Typen-> 4 Kategorien (Filme, TV Serien, Staffeln, Episoden)->eine auswählen-> jetzt über Seitenmenü die Ansicht auswählen (Wall, InfoWall, Poster, Fanart usw..) ->Speichern (auf das angezeigte Bild klicken oder auf den Text)->fertig

Nun wird die Ansicht in Lastship so dargestellt, wie sie eben eingestellt wurde

Wollt Ihr die Datenbak zurücksetzen, dann kann sie gelöscht werden

Erklärung zur Datenbank:

*views.db *

speichert eine festgelegte Ansicht über das Lastship Menü, welche bei jedem Seitenaufruf (Pfad: Bsp. Filme -> Trakt -> Sammlung) die - vom Skin in der ViewModes.db gespeicherte -ViewID überscheibt 


**Kanäle**

Hier werden Euch Sky Sparten angezeigt

Diese sind jedoch KEINE Live Streams

Die Sparten dienen nur so als Vorschlag was man schauen könnte

Englischer SkyEPG wird verwendet, Streams sind aber in deutsch

**Meine Filme / Meine TV Serien**

Diese beiden Kategorien sind nur nutzbar, wenn z.B. Trakt aktiviert ist

Hier findet Ihr dann Eure gesehenen Serien/Filme, Filmvorschläge usw.

**Nach welcher Logik werden Filme unter "neue Filme" aufgelistet**

Dort kommen nicht neueste Filme zuerst und nach hinten werden sie immer älter, sondern neue Filme stehen teilweise einfach irgendwo weiter unten in der Liste

Warum können Neuerscheinungen nicht einfach immer chronologisch von vorne ergänzt werden? 

*Antwort:*

Es zeigt die Filme des letztes Jahres (mit einer 60 tägigen Verzögerung, weil ein Film der heute ins Kino gekommen ist bringt meistens recht wenig)

Geordnet ist es nach Moviemeter

Wie genau das zusammen gesetzt ist kann bei IMDB nachgelesen werden

### Einstellungen Allgemein

*Funktionen und Einstellungen*

***Erscheinungsbild***

Es werden Icons und der Hintergrund anders dargestellt

Ansonst hat diese Einstellung keine Auswirkung

Zur Auswahl stehen in Lastship:

Lastship (Standard)

Lastship2

Exodus

Exuary

Lastship verwendet ein zugehöriges Artwork Addon für Themen Unterstützung

Das Lastship Artwork Addon wird standardmäßig mit installiert

***Zeitlimit für Index Seiten:***

*Standard (default):* 20 Sekunden

Ist die Zeit, wie lange Lastship die Anbieter durchsuchen soll  bevor das Suchergebniss , als Liste zur Auswahl  angezeigt  wird

Lastship liefert ein exzellentes Ergebnisse mit einem Wert von 12 - 15 Sekunden, vor allem wenn ihr einen Premium Service verwendet.

Wenn Ihr Schwierigkeiten habt Streams zu finden, kann dieser Wert erhöht werden

***Gesehen/Fortsetzungspunkte***

*Standard (default): Lokal*

*Lokal:* 

der gesehen Status wird innerhalb von Kodi behandelt

*Trakt:* 

wenn Ihr bei dem Menüpunkt *Konto* Euer Trakt Konto aktiviert habt, kann hier auch Trakt ausgewählt werden

Wird Trakt verwendet, dann wird der gesehen Status  auf der Trakt Homepage gespeichert 

***Sprache für Informationen***

*Standard (default):* Auto

Es wird automatisch die in Kodi verwendete Sprache benutzt

Wenn notwendig, kann die Sprache manuell eingestellt werden

Diese Einstellung kontrolliert die Sprache, welche Angezeigt/Wiedergegeben wird, wenn Lastship Abfragen von Titel, Beschreibungen und andere Metadaten Informationen, für Filme und Serien durchführt

Diese Einstellung bezieht sich nur auf die Informationen für Lastship und hat KEINE Auswirkung auf die Stream Sprache

***Sprache für Indexseiten***

Hier wird die Sprache für die Webseiten Eingestellt

Zur Auswahl steht nur German, da wir keine Fremdsprachigen Streams anbieten

**Serien-Staffeln reduzieren**

EIN: Alle Staffeln werden in einer Liste angezeigt 

AUS: Staffeln werden in eigenen Staffel Ordnern angezeigt

**Fanart verwenden**

*Standard (default):* aktiviert

Wenn Ihr Probleme mit dieser Funktion habt, solltet Ihr überlegen diese zu deaktivieren um zu sehen, ob sich dadurch die Leistung verbessert

Dadurch verliert Ihr natürlich die Bilder und Kosmetische Aspekte. Aber es könnte zur Leistungsverbesserung beitragen

**Noch nicht gesendete Staffeln/Episoden anzeigen**

*Standard (default):* aktiviert

Diese Staffeln/Episoden werden rot (Standard)  markiert angezeigt

Die Frabe kann jedoch auf eine andere umgestellt werden

**Nur Filme älter als 90 Tage anzeigen**

*Standard (default):* deaktivert

Wie die Einstellung schon sagt, werden bei aktiviert, Filme erst angezeigt wenn sie schön älter als 90 Tage sind

**Filme nach Jahrgang filtern**

Hier kann eingestellt werden, dass nur Filme aus einer bestimmten Zeitspanne angezeigt werden sollen

*MENÜ*

**Neue Filme:**

Einstellung, welcher Inhalt angezeigt wird, wenn die Kategorie Neue Filme in Lastship gewählt wird (Neue Filme in Deutsch, Im Kino, am populärsten, Empfohlen, Deaktivieren

**Neue Episoden:**

Einstellung, welcher Inhalt angezeigt wird, wenn die Kategorie Neue Episoden in Lastship gewählt wird (Trakt-Episoden, Trakt-Fortschritt, Episoden, Deaktiviert)

**Meine Listen (Trakt/IMDb):**

wenn aktiviert, wird im Hauptmenü die Kategorie Meine Liste angezeigt

Funktion nur mit Trakt Konto (und anderen Konten)

**Schnelle Suche**

*Standard (default):* deaktivert

Wenn aktiviert, erscheint ein kleines Popup Fenster, wo sofort gesucht werden kann

Unterschied zur Normalen Suche ist nur, dass man weniger klicken muss

Der Suchverlauf wird hier ebenfalls gespeichert

*Trakt Bibliothek Automatisch Synchronisieren*

In Lastship unter:

Werkzeuge - Einstellungen (Allgemein) findet Ihr ganz unten "Trakt Bibliothek Automatische Synchronisierung"

Hier kann auch gewählt werden: 

Synchronisierung bei Kodi Start oder in der 2. Zeile einen Zeitintervall einstellen 

Dadurch es nun möglich, das lokale Trak.tv Filme/Serien automatisch mit dem Trakt.tv Server synchronisiert werden (gesehen Status)

Hierbei ist es egal ob die Filme/Serien in der Bibliothek liegen, oder nur in den Favouriten, sie werden auf jeden Fall synchronisiert

Funktioniert mit Kodi Favouriten und auch mit SuperFavouriten

In der oberen Ecke wird der Synchronistations Vorgang angezeigt

**Nightly Update**

Unter Werkzeuge - Einstellungen (Allgemein) findet Ihr ganz unten die Funktion Nightly Updates

Wird diese Einstellung aktiviert, muss Lastship einmal verlassen werden

Im Anschluss befindet sich ein neuer Menü Eintrag, Nightly Updates, in Lastship 

Lastship wird nur aktualisiert, wenn auf *Nightly Updates* geklickt wird

Die ~Nightly ist eine Entwickler Version und kann auch Fehler beinhalten

Es sollte gut überlegt werden diese Funktion zu nutzen

Am besten nutzen es User, die auch wissen wie sie wieder zu einer funktionsfähigen Version zurückspringen können

Sollte ein Update Fehlerhaft sein, so geht wie folgt vor:

Im Ordner ....kodi / addons befindet sich ein Ordner mit plugin.video.lastship, diesen Ordner löschen

Im Anschluss Lastship aus dem Repo installieren

**Fehlerhafte Provider erkennen**

Diese Funktion hilft den Entwicklern bei der Fehlersuche und jeder User kann hierbei mithelfen

Sollte mal ein Provider seinen Seitenaufbau ändern und das Plugin nicht mehr funktionieren wird das mit diesem Feature erkannt und der Provider wird vorübergehen nicht mehr verwendet

*Aktiviert stehen folgende Settings zur Verfügung:*

Anzahl Errors für Deaktivierung: 

Wie oft darf ein Provider einen unbekannten Error werfen bevor er deaktiviert wird

Deaktivierten Provider überprüfen nach Stunden: 

Ist ein Provider deaktiviert wird er nach X Stunden wieder freigeschalten und der Error-Counter auf 0 gesetzt

Damit können eventuelle Updates oder wieder online kommen des Providers automatisch berücksichtigt werden

Ein Löschen des Indexseiten-Speichers setzt die Statistiken und Deaktivierungen zurück

Wenn diese Funktion aktiviert ist, dann sendet Lastship Fehlerhafte Index Seiten-Informationen an unseren Forum Server

Es sendet einmalig, sobald ein Fehler erkannt wird

Es sendet den Namen der Indexseite 

### Einstellungen Wiedergabe

**Standard Aktion (default):**   Verzeichnis

*Verzeichnis*

Die Anzeige ist wie eine Liste Aufgebaut

*Dialog*

Die Anzeige erfolgt in einem kleineren Fenster, Aufbau wie eine Liste
 
*Auto-Play*

Es wird keine Liste angezeigt

Die Wiedergabe nach Filmauswahl/Serienauswahl startet automatisch

Es wird der beste verfügbare Hoster & die beste verfügbare Qualität gewählt

Die Auswahlreihenfolge der Hoster richtet sich nach deren Priorität (und auch Qualität, HD vor SD usw.)

Die Priorität kann im URLResolver unter “Resolver Settings” angepasst werden.

***Niedrige Werte werden vor hohen Werten gewählt***

**Fortschrittsdialog**

Vordergrund: 

nach Streamauswahl wird das Info-Fenster, groß in der mitte des Bildschirmes dargestellt

Hintergrund: 

nach Streamauswahl wird das Info-Fenster, klein am Rand des Bildschirmes dargestellt

**Dateianbieter-Filter**

**Höchste Qualität:**

4k, 1440p, 1080p, 720p und 480p stehen zur Auswahl

Das was hier engestellt wird, ist die max. Auflösung nach der die Index-Seiten durchsucht werden. 

Ist auch die max. Auflösung, welche bei Autoplay verwendet wird

Bei Seriesever ist 4k verfügbar, aber nur mit einem Premium Account (Bezahlung)

**Nur SD Anbieter in Autoplay**

*Wenn aktiviert:*

werden im Auto-Play Modus nur SD Streams wiedergegeben. 

HD Streams werden dabei ignoriert

Ist nur dann sinnvoll, wenn man einen langsamen Internet Anbieter oder eine schwache Hardware hat

**Zusatzinfo für Quellen anzeigen**

Es werden dann neben dem Stream noch weiter Infos (wenn verfügbar) angezeigt, z.B. die Audioqualität

**HEVC**

Streams mit HEVC anzeigen (h.265 Codec)

HEVC wird nicht von jeder Android Box unterstützt

**Dateianbieter mit Pairing (Captcha)**

Wenn deaktiviert, werden alle Hoster die Captcha-Abfragen durchführen ignoriert

**Nach Index-Seiten sortieren**

Wenn aktiviert, werden nur die Streams der Ausgewählten Anbieter angezeigt

Premium Services sind immer Gruppiert und stehen  an der Spitze der Liste

Beispiel: Alle Streams, die z.B. über Premiumize gefunden werden, sind aufgelistet, dann erst "normale" Anbieter

***Nur Premium Quellen anzeigen***

*Standard (default):* deaktiviert

Wenn aktiviert, werden nur Premium Streams (Bezahlstreams von z.B. Premiumize, RealDebrid usw) angezeigt

*Bei Wiedergabe Start...*

**Fortsetzen**

Wenn ein Stream gestoppt wird, wird automatisch  ein Fortsetzungspunkt gespeichert/erstellt (aber erst ab einer Wiedergabezeit von 3 Minuten )

*Option Wiedergabe fortsetzten EIN:*

Es erscheint bei Fortsetzung des Streams eine  Anzeige  wo gewählt werden kann: 

Fortsetzen oder Vom Anfang abspielen an, egal welcher Hoster dabei gewählt wird

*Option Wiedergabe fortsetzten AUS:*

Stream startet immer vom Anfang (auch wenn Ihr eine advancedsettings.xml verwendet)

**Automatisch Fortsetzen**

Angespielte Streams werden automatisch an der Stelle fortgesetzt, wo sie zuvor gestoppt wurden

*Bei Wiedergabe-Ende:*

**Verzeichnis neu laden (Container-Aktualisierung erzwingen)**

*Standard (default):* deaktiviert

*Verzeichnis neu laden* ist eine Kodi-interne Funktion

Sie bewirkt, dass das aktuell geöffnete Verzeichnis neu eingelesen wird

Dadurch sollte der Trakt-Status aktualisiert werden, nachdem man einen Film / eine Episode gesehen hat

Weil das nicht auf jedem Gerät so funktioniert hat wie es sollte, hat man eine Option draus gemacht

Für die meisten ist es wohl am besten, das zu deaktivieren (ist auch die Standrard-Einstellung), weil es nur Zeit kostet

Wenn in Kodi unter: 

Addons-Seitenmenü, Automatische Aktualisierung auf AUS gestellt ist, wird Lastship nicht automatisch aktualisiert

## 2.3 Index Seiten Aktivieren und Deaktivieren

*Standard:* Alle Index Seiten aktiviert, außer die Seiten wo ein Benutzerkonto erforderlich ist (Serienstream, VodHD usw.)

In Lastship, unter dem Menüpunkt Werkzeuge, *Index-Seiten*, besteht die Möglichkeit bestimmte Seiten an bzw. auszuschalten, wenn kein Interesse an bestimmten Seiten besteht

Diese werden dann auch nicht in der Suche angezeigt

Ebenso besteht hier die Möglichkeit, die Funktion "Lokale Dateien (Bibliothek)" einzuschalten

Dann werden auch die lokal gespeicherten Filme/Serien mitgesucht

Einige Index-Seiten unterschützen Multi-Part

Aktuelle sind das ddl.me und Filmpalast

*Was ist MultiPart?*

MultiPart bedeutet: das der Film in zwei Teilen auf der Seite hochgeladen ist und Lastship diese nahtlos nacheinander abspielt

Der Film sollte auch grob in der Mitte mal nachladen, beim Wechsel auf den zweiten Stream

Auch beim Start des zweiten Stream etwas langsamer, aber besser so als gar nicht

*Anmerkung:*

Wenn Ihr Probleme mit kinox habt, hilft es wenn Ihr Eure DNS (z.B. auf die von Google 8.8.8.8) Adresse ändert

Manche Seiten werden von den Internet Providern geblockt 

Nache einem Lastship Update werden auch neu hinzugefügte Seiten automatisch angezeigt

Das Update erfolgt aber nur, wenn das Lastship Repo installiert ist, wie am Anfang beschrieben

Im Verzeichnis ...kodi/addons/plugin.video.lastship/resources/lib/sources/de sind die .py Daten der einzelnen Webseiten abgelegt 

Hier könnt Ihr auch neue Deutsche Seiten hinzufügen, oder bestehende bearbeiten

Bei diesem Pfad handelt es sich um "versteckte Dateien"

Diese müssen erst sichtbar gemacht werden

**In Lastship befindet sich jetzt der erste legale Streaming Anbieter, Amazon**

Dieser Anbieter ist als Standard "DEAKTIVIERT", da er NUR mit einem gültigen Amazon Prime Video Konto funktioniert

Ebenso ist es zur Zeit (noch) nicht möglich, Amazon mit Kodi 18 zu nutzen

Und eine weiter Einschränkung ist, zur Zeit KEINE Inputstream Funktion in Kodi 17

*Um Amazon in Lastship verwenden zu können ist folgendes zwingend notwendig:*

Es muss das Video Addon AmazonVOD, vom Sandmann Repo installiert sein, da Lastship über dieses Addon arbeitet

Das Sandmann Repo bekommt man hier: [Link](https://github.com/Sandmann79/xbmc/blob/master/packages/repository.sandmann79.plugins/repository.sandmann79.plugins-1.0.2.zip)

## 2.4 Hosterwahl

Wenn Ihr im Menü z.B. Filme- Jahr- 2017- beliebigen Film auswählen- klickt, werden alle verfügbaren Anbieter/Hoster durchsucht.

Auch nachdem eine Suche gestartet wurde, werden alle verfügbaren Anbieter/ Hoster angezeigt. 

Die Anzeige sieht wie Folgt aus:

BS | OPENLOAD | HD | 5.1

(Anbieter | Hoster | Qualität|z.B Audio, optionale Zusatzinfo)

Die Qualität des Streams (als optionale Zusatzinfo) kann sein:  4k, HD, SD, CAM usw.

Wie lange das durchsuchen der Hoster dauert hängt von der Einstellung *Zeitlimit für Index Seiten* ab

*Wenn Ihr einen Film/Serie angewählt habt, könnt Ihr ein zusätzliches Menü (Kontexmenü) öffnen:*

am PC: rechte Maus Taste

am Handy/Tablet: langer Druck auf den Film

am FireTV: die Menü Taste drücken

Ist der von Euch gewählte Anbieter/Hoster nicht verfügbar, nimmt Lastship AUTOMATISCH den nächsten, bis ein lauffähiger gefunden wird

***Anmerkung zu den Hostern Openload (HD), TheVideo, Flashx:***

Wenn Ihr einen dieser Hoster zum Streamen auswählt, erscheint ein Fenster, welches Euch auffordert Eure Gerät zu Pairen

Das könnt ihr mit ruhigen Gewissen machen

Ihr müsst im selben WLAN sein wie das zu Pairende Gerät (z.B. FireTV, Apple TV usw.)

Für Flashx müsst Ihr Euch auf Flashx.tv/Flashx.sx ein Benutzerkonto anlegen, dafür kann auch eine Wegwerf E-Mailadresse verwendet werden

Öffnet am Handy/Tablet/PC einen Browser mit der angezeigten Adresse von openload (http://olpair.com/) bzw. 

thevideo (https://tvad.me/pair) bzw. 

flashx (https://www.flashx.tv/pair oder www.flashx.sx/pair)

(Klickt in dem Kasten bei “Ich bin kein Roboter”)

Dann ganz runter und klick auf “Pair”

Das wars

Dieser Vorgang muss immer wieder Wiederholt werden (nach 3-4 Stunden oder 5 Streams)

*Warum ist das "pairen" nötig?*

Auf der Homepage muss immer eine Werbung betrachet werden

Da wir ja die Homepage des Hostbetreibers nicht besuchen müssen, entgehen dem Betreiber Werbeeinnahmen. 

Damit dies nicht der Fall ist und die Hoster Lastship so arbeiten lassen, wurde mit den Betreibern diese "pair" Funktion vereinbart.

Durch den klick auf "pair" bekommen die Hoster Ihre Werbeeinnahme.

Für Euch entstehen dadurch KEINE Kosten!!

## 2.5 Konten

In dieser Einstellung, können Benutzerdaten von Webseiten eingetragen

Es steht eine Vielzahl an Anbietern zur Verfügung z.B. Trakt, TMDb, IMDb Seriesever, usw

Voraussetzung ist natürlich, dass ein Konto vom jeweiligen Anbieter vorhanden ist

Bei vielen Anbietern, kann zur Registrierung eine Wegwerf E-Mailadresse verwendet werden, ggf. mehrere Anbieter probieren

Premiumdienste wie zum Beispiel RealDebrid, Premiumize usw. werden im URLResolver konfiguriert und in Lastship dann farblich dargestellt

In Lastship kann über *URLResolver Einstellungen-Universelle Resolver* darauf zugegriffen werden

Premiumdienste wie zum Beispiel VodHD werden in Lastship konfiguriert und werden daher NICHT farblich dargestellt

**Fanart tv**

Auf der Homepage [https://fanart.tv/](https://fanart.tv/), durch klick auf Register, ein Benutzerkonto erstellen

Es kann auch eine Wegwerf/Einmal E-Mailadresse verwendet werden

An die angegebene E-Mailadresse wird ein Bestätigungslink geschickt

Nach dem Klick auf den Link, erfolgt eine Aufforderung, ein neues Passwort einzugeben. Durchführen und Klick auf *Reset Passwort*

Zurück zur Homepage und Einloggen

Am unteren Ende der Homepage steht API und *Create API Key*, auswählen

Klick auf *Generate Personal API Key*

Es wird nun der Fanart API Key angezeigt, welcher dann in Lastship eingetragen wird

**TMDB (The Movie Database)**

Auf [https://www.themoviedb.org/](https://www.themoviedb.org/) Registrieren und ein Benutzerkonto anlegen, Captcha lösen, fertig

Es kann eine Wegwerf E-Mailadresse verwendet werden, ggf mehrere Anbieter probieren

Es wird dann ein Bestätigungslink an die angegebene E-Mailadresse gesendet

Den Link in der E-Mail, in den Browser kopieren und Anmelden, Fertig

Das TMDB Konto ist nun erstellt

Lastship verwendet einen allgemeinen TMDB API-Key, den ALLE User verwenden

Es kann jeder User einen persönlichen TMDB API-Key anfordern und diesen in Lastship eintragen (z.B. wenn es Probleme mit den Artwork Bildern gibt)

*TMDB API-Key anfordern:*

- Mit Eurem Konto anmelden und rechts oben auf das "Benutzerssymbol" klicken

- Einstellungen wählen

- unter Settings, am linken Rand, API wählen

- auf "Create" klicken

- Developer wählen

-  Approve Terms of Use (AGB's), ganz unten Akzeptieren

- Es öffnet sich nun ein Fenster: API Schlüssel anfordern, wo die Eingabefelder mit erfundenen Daten ausgefüllt werden (somit gibt es keinen Bezug zu Eurer wahren Identität)

- im Anschluss auf "Erstellen" klicken

- nun wird unter Einstellungen - Settings - API - Details der  *API Schlüssel (v3 auth)* angezeigt. Dieser wird nun in Lastship eingefügt

- unter "Stats" ist ersichtlich, wie viele Zugriffe es mit diesem API-Key gegeben hat

Dieser API Key kann auch im Metahandler eingetragen werden, wenn Ihr es möchtet (siehe weiter unten TVDB Konto)

**Trakt Konto einrichten:**

Trakt.tv bietet viele Möglichkeiten, wie z.B. das Synchronisieren des Fortsetzungspunktes auf deren Server

Auf Trakt.tv ein Konto erstellen

In der Kategorie *Konto* - *Trakt* auf Berechtigung klicken

*Es wird ein Infofenster angezeigt:*

Webseite besuchen: https://trakt.tv/activate

Dort werdet Ihr dann aufgefordert den Code (der in Lastship angezeigt wird)  einzugeben, Continue

Allow Lastship to use Your Accout (Erlaube Lastship die Verwendung Deines Kontos), YES

WooHoo! Your device is now connected and will automatically refresh in a few seconds (Dein Gerät ist jetzt verbunden und wird in wenigen Sekunden automatisch aktualisiert)

Zurück in Lastship, steht jetzt bei Trakt Euer Benutzername

Der Takt Service kann ab jetzt genutzt weren

Um bestimmte Funktionen von Trakt nutzen zu können (z.B. Fortsetzungspunkt synchronisieren), ist es notwendig, das Original Trakt Addon (Scrobbler) aus dem offiziellen Kodi Repo (Standard in Kodi), zu installieren

Weiteres zu Trakt und Funktionen von Trakt steht im Kapitel 2.9

**IMDb**

Damit User ein eigenes IMDB Konto erstellen können geht man wie folgt vor:  
  
Es kann für die Registrierung auch eine Wegwerf E-Mailadresse verwendet werden  
  
1\. Ruft die Seite [http://www.imdb.com/](http://www.imdb.com/) auf  
  
2\. Geht auf [https://www.imdb.com/registration/signin...usr\_lgin\_1](https://www.imdb.com/registration/signin?u=/&ref_=nv_usr_lgin_1) und dann auf [Create a New Account](https://www.imdb.com/ap/register?clientContext=131-7328379-0261356&openid.pape.max_auth_age=0&openid.return_to=https%3A%2F%2Fwww.imdb.com%2Fap-signin-handler&openid.identity=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.assoc_handle=imdb_us&openid.mode=checkid_setup&siteState=eyJvcGVuaWQuYXNzb2NfaGFuZGxlIjoiaW1kYl91cyIsInJlZGlyZWN0VG8iOiJodHRwczovL3d3dy5pbWRiLmNvbS8_cmVmXz1sb2dpbiJ9&openid.claimed_id=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0&&tag=imdbtag_reg-20)  
  
3\.Geforderte Daten angeben, und dann Registrieren 
  
Im Anschluss bekommt man ein E-Mail, welche bestätigt werden muss um das Konto zu aktivieren  
  
Dieser Bestätigungslink, öffnet auf IMDb noch ein Feld, in dem eine Captcha Abfrage durchgeführt wird, und dann durch Klick auf  "Submit" bestätigen
  
4\. Nach dem Anmelden Loggt man sich über das Login Feld ein, und schon hat man sein Profil erstellt  
  
5\. Um an die ID zu kommen, klickt man auf seinen Profilnamen, der oben rechts auf der Seite angezeigt wird  
  
6\. In der Browser URL, wird nun ganz einfach die Zahlenkombination, ohne die Buchstaben, herauskopiert
  
7\. Hinterlegt diese Daten dann direkt im Lastship Konto und bestätigt es mit OK!  
  
8\. Viel Spaß beim nutzen deines Kontos in Lastship!

**Serienstream und Seriesever**

Serienstream und Seriesever gibt es nicht viel zu erklären. Einfach auf der jeweilgen Homepage ein Benutzerkonto erstellen und dann Benutzername, E-Mail und Passwort in Lastship eintragen

**TheTVDB**

Dieses Konto kann nicht in Lastship eingetragen werden, sonder NUR im *Metahandler*

Damit jedoch alle verfügbaren Konten hier zusammen stehen, wird der TVDB API-Key trotzdem erklärt

Es besteht die Möglichkeit eigene API Keys im Metahandler einzutragen

Der Metahandler verwendet einen allgemeinen TVDB API-Key und einen TMDB API-Key, den ALLE User verwenden

Es kann jeder User aber auch einen persönlichen API-Key (Zugangsschlüssel) anfordern und diesen im Metahandler eintragen 

Voraussetzung ist natürlich, dass ein Konto vom jeweiligen Anbieter vorhanden ist

Auf  https://www.thetvdb.com/ Registrieren und ein Benutzerkonto anlegen, dazu auf login klicken

Im Anschluss auf „Register for an account“ klicken

Es wird dann ein Bestätigungslink an die angegebene E-Mailadresse gesendet

Den Link in der E-Mail bestätigen, Fertig

Das TVDB Konto ist nun erstellt

Um nun den API Key zu erhalten, ist es notwendig, sich anzumelden

Im Anschluss daran folgend Link besuchen/öffnen: https://www.thetvdb.com/?tab=apiregister

Am unteren Ende steht: Project Name und Project Website

Hier muss irgendetwas (beliebiges) eingetragen werden

Dann auf „Retrieve API Key“ klicken und man bekommt den TVDB API Key

Dieser Key kann dann im Metahandler eingetragen werden

*Der Metahandler ist hier zu finden:*

Einstellungen- System – Addons – Abhängigkeiten verwalten – metahandler

Das Kontexmenü öffnen und Einstellungen wählen

Nun kann unter TMBD oder TVDB der eigene Key (Schlüssel) eingegeben werden

**VodHD.to**

VodHD muss unter Index Seiten, in Lastship, extra aktiviert werden

Zusätzlich muss in Lastship unter Wiedergabe - Höchste Qualität, 4K eingestellt sein, damit der Anbieter angezeigt wird

Dieser Anbieter (Index Seite/Webseite) ist ein Premium Anbiter für den bezahlt werden muss

Informationen zum Anbieter sind hier zu finden: https://vodhd.to/

Auf der Webseite VodHd ein Benutzerkonto Anlegen

Bezahlt werden kann z.B. mit Bitcoins, Paysafecard usw.

*Anleitung zum sichern bezahlen mit Paysafecard:*

1. Seite https://www.wkv.com/ besuchen und gewünschten Betrag wählen (5€)

2. Neues Kundenkonto Anlegen und alle folgenden Schritte bis zur Bezahlung befolgen

3. Nach der Bezahlung wird die Paysafecard angezeigt bzw. per E-Mail zugeschickt

   Diese Paysafecard muss dann später auf VodHD hochgeladen werden
 
   Paysafcard kann auch im Handel erworben werden, dann muss die Karte abfotografiert oder eingescannt werden

4. Auf VodHD anmelden

5. Nach dem Kauf öffnet ihr ein [Supportticket](https://www.vodhd.to/forum/index.php?/support/)durch klick auf "Neue Supportanfrage erstellen" und gebt dort die Daten der Paysafecard an und ladet den Scan/Foto hoch
Als Titel bietet sich an "Account aktivieren" zu schreiben

Die Daten werden gecheckt und innerhalb von 24 Stunden (bis zu 3 Tagen)  werden die Accountdaten für den Premiumzugang zugesendet

Es werden 3 wichtige Informationen für das Lastship Konto benötigt, welche sich in der zugesendeten E-Mail befinden oder Ihr findet diese Informationen zusätzlich auch auf VodHD (rechts oben der Brief) unter Nachrichten:

Login, Passwort, Streama-URL

StreamURL komplett so in Lastship eintragen wie sie zugesendet wurden: http://IP Adresse:Port

## 2.6 Untertitel

*Standard (default):* deaktiviert

Um Untertitel zu aktivieren, gehen in den Einstellungen zu Kategorie *Untertitel*

Untertitel aktivieren

Hauptsprache und Zweitsprache wählen

(Es ist jedoch möglich, dass diese Einstellung Funktionslos bleibt)

Während der Stream läuft könnt Ihr nun am unteren Rand, die Untertitel ein/ausschalten

## 2.7 Downloads

Kategorie *Werkzeuge*, Lastship Downloads

Herunterladen aktivieren

Speicherplatz Ordner für Filme bzw. Serien anlegen/auswählen

Zurück zur Film/Serien Auswahl

Einen Film/Serie suchen, Film auswählen.

Wenn dann die Anbieter/Hoster angezeigt werden, das Kontexmenü öffnen

Download wählen

Es öffnet sich ein Fenster, wo der Name des Films und die Dateigröße angezeigt wird

Nach Klick auf Confirm, starte der Download

Es wird kurz: *Download in Progress* angezeigt

Während des Downloads wird in unregelmäßigen Abständen der Downloadfortschritt angezeigt (ca. 3-5 mal bis zum Ende)

Ihr findet den Film/die Serie dann in Eurem Download Ordner

**Speicherort der TV Serien (TV Shows) & Filme (Movies)**

Die Einstellung befindet sich in Lastship unter:

Werkzeuge- Lastship: Bibliothek - Bibliothek: Einstellungen

oder anderer Weg

Werkzeuge - Einstellungen: Allgemein - Bibliothek

Wie diesee Pfade in die Kodi Bibliothek eingebunden werden können, steht in Kap.2.11

Serien Pfad:  *...userdata/addon_data/plugin.video.lastship/TV Shows*

Filme Pfad:   *...userdata/addon_data/plugin.video.lastship/Movies*

Ihr könnt den Pfad auch ändern

*Wenn Ihr den Pfad nicht auf einen Pfad Eurer Wahl (z.B. Netzwerk) ändern könnt (weil das Feld "ausgegraut" ist, dann geht wie folgt vor:*

- Kodi Starten und geöffnet lassen

Dann mit dem Windows Explorer/ES File Explorer zu dem oben angeführten Pfad gehen und den Ordner löschen

Zurück in Kodi kann nun der Wunschpfad eingetragen werden

## 2.8 URL Resolver Konfiguration

Es besteht die Möglichkeit, in den Einstellungen des URL Resolvers die Priorität der Hoster festzulegen also welche Hoster als ersters angezeigt bzw. verwendet werden sollen.

Diese Einstellungen werden in der settings.xml gespeichert.

Diese befindet sich hier und kann auch auf ein anderes System kopiert werden:

 ....kodi/userdata/addon_data/script.module.urlresolver

**Jedoch aufgrund der Arbeitsweise von Lastship wird diese Einstellung im Lastship Addon nicht unbedingt berücksichtigt**

*Da Lastship & xStream den gleichen URL Resolver verwenden, hat diese Einstellung auch Auswirkung auf beide Addons!!*

Lastship probiert automatisch alle verfügbaren Hoster aus, bis ein Stream abgespielt werden kann

Die Auswahlreihenfolge der Hoster richtet sich nach deren Priorität

Diese kann unter “Resolver Settings” angepasst werden.

***Niedrige Werte werden vor hohen Werten gewählt***

Sind Eure Priorisierten (Lieblings) Hoster nicht nicht verfügbar, nimmt Lastship den nächsten Hoster der funktioniert

**Direkten Zugriff auf den URL Resolver geht über Lastship wie folgt:**

Einstellungen - Konten - Debrid-Dienste

Den URL Resolver findet Ihr in Kodi:

Optionen - Einstellungen - Addons - System Addons - Abhängigkeiten - URL Resolver:  Konfigurieren

Den URL Resolver findet Ihr in Kodi 17:

Einstellungen - System - Addons - Abhängigkeiten verwalten - URLResolver: Konfigurieren

## 2.9 Trakt

Die Einrichtung des Trakt Kontos steht in Kapitel 2.5

Um bestimmte Funktionen nutzen zu können (z.B. Fortsetzungspunkt synchronisieren), ist es notwendig, das Trakt Addon (Scrobbler) aus dem offiziellen Kodi Repo zu installieren

Der "gesehen" Status wird auch OHNE Trakt Addon, von Lastship selbst, auf den Trakt Server übertragen

*Wollt Ihr nun eine komplette Serie oder Staffel zu einer Trakt Liste hinzufügen, geht das wie folgt:*

Komplette Serie oder Staffel suchen, Kontexmenü öffnen- Trakt Manager

In dem sich nun öffnenden Fenster, könnt Ihr eine Liste wählen, wo die Serie/ Staffel gespeichert werden soll

**Kategorie:  Meine TV Serien**

In Meine TV Serien Kategorie, findet Ihr die zuvor angezeigten Listen und somit, die von Euch gespeicherten Serien/Staffeln

*Angefangene/nicht beendete Episoden:*

Für diese Funktion ist  das offizelle Trakt Addon aus dem Kodi Repo notwendig 
 
Diese Kategorie zeigt die 10 neusten/letzten Episoden, welche angefangen wurden zu schauen, jedoch nicht zu Ende geschaut wurden

Soll eine Episode vorzeitig  aus dieser Liste gelöscht werden, so muss diese als "watched in Trakt (In Trakt angesehen)" markiert werden und eventuell Cache löschen

*Wollt Ihr nun eine Staffel oder Episode in Trakt als gesehen markieren, geht das wie folgt:*

Serie wählen - Staffel wählen - Episode wählen - Kontexmenü öffnen - Watched in Trakt (In Trakt angesehen) klicken

Auf die gleiche Weise, könnt Ihr auch die komplette Serie als "In Trakt gesehen" wählen

*Wollt Ihr nun einen Film zu einer Trakt Liste hinzufügen, geht das wie folgt:*

Das vorgehen ist dabei gleich wie bei den Serien

Film wählen - Kontexmenü öffnen - Trakt manager 

In dem sich nun öffnenden Fenster, könnt Ihr eine Liste wählen, wo der Film gespeichert werden soll

**Kategorie:  Meine Filme**

In dieser Kategorie, findet Ihr die zuvor angezeigten Listen und somit, die von Euch gespeicherten Filme

*Wollt Ihr nun einen Film in Trakt als gesehen markieren, geht das wie folgt:*

Film wählen - Kontext Menü öffnen - watched in Trakt (In Trakt angesehen) wählen

*INFO:*

Immer wenn ein Film/Serie in Lastship als gesehen oder "In Trakt gesehen" markieret wird, springt Lastship zum Listenanfang zurück

Das ist leider ein normales verhalten von Lastship und liegt an Kodi 

Auch wenn Trakt nicht genutzt wird in/mit Lastship, benutzt Lastship trotzdem die Suche von Trakt.tv

Ihr könnt auf der Homepage von Trakt.tv, Filme&Serien selbst zur Trakt Datenbank hinzufügen/nachtragen, wenn diese nicht vorhanden sind

Dazu benötigt Ihr die Film oder Serien ID Nummer, welche Euch auf thevdb.com angezeigt wird

Am unteren Ende der Trakt Homepage, findet Ihr das Import Menü für Filme (Import Movie) und Serien (Import TV Show), hier müsst Ihr die ID Nummer eingeben

## 2.10 Gemeinsamer gesehen Status in Lastship und xStream

Lastship benutzt standardmaäßig den metahandler

Wenn dieser auch in xStream aktiviert wurde, dann wird der gesehen Status aus xStream auch in Lastship angezeigt und umgekehrt, weil dann beide Addons in die gleiche Datenbank schreiben

Die Datenbank befindet sich unter:  

.....kodi/userdata/addon_data/Skript.module.metahandler/meta_cache/Video_cache.db

Ihr könnt den "gesehen Status" (wached state) auch exportieren und auf einem anderen System importieren

Ihr müsst dann also nur die oben genannte *video_cache.db* auf ein anderes System übertragen

Thema: [Link](http://xstream-addon.square7.ch/showthread.php?tid=787)

## 2.11 Lastship Bibliothek

Eine sehr nützliche Funktion ist die Integration von Lastship Streams in die Bibliothek

Somit hat man seine lokale Bibliothek und die Online Streams übersichtlich in EINER Bibliothek vereint

Streams in der Bibliothek werden erst als *gesehen* markiert, wenn Sie komplett zu Ende gesehen werden oder man setzt den "gesehen Status" über das Kontexmenü selbst

Es ist *nicht* möglich innerhalb der Bibliothek eigene Ordner zu erstellen und somit lokale Streams von Online Streams zu trennen

(Eventuell bietet ein anderes Skin diese Möglichkeit)

Eigene Ordner sind Sachen die Ihr in Kodi regeln müsst

Lastship selbst legt nur eine Datei ab, so dass Kodi diese Datei annimmt

Es besteht *nicht* die Möglichkeit, zu sehen, ob eine Neue Folge einer Serie bei dem Provider XY erschienen ist

Wenn Ihr eine Serie, einen Film zur Bibliothek hinzufügt, erzeugt Lastship (im weiter unten angeführten Pfad) .strm & .nfo Dateien

Die Informationen dafür kommen von den Online Datenbanken (TVDB, IMDB, The Movie DB usw.)

Aufgrund dieser Informationen, werden die .strm Dateien erzeugt

In der .strm steht im Endeffekt nur drin "Spiel mal IMDB-ID xy ab"

Es werden dabei weder die Anbieter noch die Hoster mit Anfragen/Abfragen belastet

Erst wenn eine Episode ausgewählt wird, erfolgt eine Anfrage/Abfrage bei den Anbietern & Hostern

Die .nfo ist nur eine Hilfe für den Scraper

*Beispiel:*

Die Serie Flash. Es gibt 2 Serien mit dem exact dem gleiche Namen

In der .nfo ist ein Link zu z.b TVDB

So weiß der Scraper ganz genau um welche Serie es sich handelt, damit nicht die falschen Meta-Daten geladen werden

Wenn Ihr eine Film oder eine Serie aus der Bibliothek löscht, erscheint sie beim nächsten aktualisieren der Bibliothek wieder

Daher müsst Ihr die Datei aus dem Ordner (Speicherpfad der .strm) selbst entfernen

**Bibliothek Anpassung an neues Addon (.strm Dateien von einem Addon, in einem anderen Addon verwenden/anpassen)**

Lastship, Placent und Incursion sind gleich aufgebaut und bieten quasi dieselben Features

In jedem Stream, den Ihr über eines der genannten Addons in die Bibliothek mit aufgenommen habt, wird gespeichert welches Addon das war

Dies ist nötig, damit der Stream zum Abspielen, auch dem entsprechenden Addon zugewiesen werden kann

Ändert man aber nun das Addon, können alle Einträge der Bibliothek nicht mehr abgespielt werden und sind somit nutzlos

Man müsste nun theoretisch alle Stream Dateien einzeln mit einem Editor öffnen und manuell an das andere Addon anpassen oder die komplette Bibliotek neu hinzufügen

Daher hier einige Möglichkeiten, welche mithilfe eines Programms nach kurzen Einstellungen alles automatisch und innerhalb kürzester Zeit erledigt

Beispiel:

alles auf Lastship umstellen

**1.Möglichkeit:**

Ladet euch folgendes Programm für euren Windows Rechner herunter: [grepWin](https://sourceforge.net/projects/grepwin/files/)

1. Installiert das Programm und startet es

2. Folgende Einstellungen vornehmen oder überprüfen:

    *Search in:*
    
     Quelle zum  Filme und Serien Ordner z.B. C:\ 

    (nutzt ihr einen NAS, dann fügt diesem am besten vorher einen Laufwerksbuchstaben hinzu)

    *Search:*
    
     hier muss Regex Search ausgewählt werden
     
    *Search for (suchen nach):*
    
    Um alle .strm's von Placenta und Covenant (in einem Arbeitsgang) auf Lastship "umzubenennen" , tragen wir ein "placenta|covenant" (durch das "|"  können wir gleich nach beidem suchen)
     

    *Replace with (ersetzen durch):* 
    
    Da wir auf Lastship umsteigen, schreiben wir hier "lastship"
     
    *Limit Search:* 
    
    setzt einen Haken bei include subfolders und schreibt bei File Names Match "*.strm"
     
    Achtet bitte darauf, dass Text match ausgewählt wird und NICHT Regex wie oben!

3. Jetzt klickt ihr einfach auf Replace und wartet ab.

4. Fertig

**2.Möglichkeit:**

Ladet Euch [Note++](https://notepad-plus-plus.org/) herunter und installiert es

Dann gibt es oben den Reiter Suchen, auswählen

In Datei Suchen, wähle *Find in Files*

Folgende Felder ausfüllen: 

Suche nach, Ersetzten durch und Verzeichnis

Bei Groß/Kleinschreibung beachten einen Haken setzen

Alle suchen klicken.Nach diesem Vorgang, wähle Ersetzen in Dateien

Das war es 

**Serien automatisch aktualisieren**

*Wann wird das gemacht?*

Das passiert beim Start von Kodi

Wenn jemand eine neue Folge deiner Serien einträgt (normal passiert das bei Ausstrahlung) wird diese Automatisch hinzugefügt

Beim Start von Kodi sollte eine kleine Meldung zu sehen sein

Ist es nicht erwünscht, das bei jedem Kodi Start die (Lastship) Bibliothek aktualisiert wird, dann kann dies in Lastship deaktiviert werden:

- Lastship - Werkzeuge - Bibliothek - Einstellungen

TV-Serien automatisch aktualisieren: deaktivieren

Das aktualisieren, muss dan selbst gemacht werden:

- Lastship - Werkzeuge - Bibliothek

Bibliothek updaten klicken
  
**Erklärung Menüpunkte:**

*Bibliothek nach dem Hinzufügen von Inhalten aktualisieren:*

heißt das ein Refresh der lokalen Bibliothek durchgeführt wird nach, dem Hinzufügen

Sprich Kodi prüft auf neue Daten

Wenn man das Deaktiviert macht Kodi das nur beim ersten Neustart

*TV Serien automatisch aktualisieren:*

 fügt neue Folgen zur Kategorie Serien hinzu
 
 Der Intervall dafür liegt bei 6 Stunden

*Es wird in der Kodi Bibliothek in 2 Kategorien unterschieden:*

Serien & Filme

**Speicherort der TV Serien (TV Shows) & Filme (Movies)**

Dieser Speicherort ist wichtig, da Ihr diesen zur Bibliothek selbst hinzufügen müsst

Die Einstellung befindet sich in Lastship unter:

Werkzeuge- Lastship: Bibliothek - Bibliothek: Einstellungen

oder anderer Weg

Werkzeuge - Einstellungen: Allgemein - Bibliothek

Serien Pfad:  *...userdata/addon_data/plugin.video.lastship/TV Shows*

Filme Pfad:   *...userdata/addon_data/plugin.video.lastship/Movies*

Ihr könnt den Pfad auch ändern

*Wenn Ihr den Pfad nicht auf einen Pfad Eurer Wahl (z.B. Netzwerk) ändern könnt (weil das Feld "ausgegraut" ist), dann geht wie folgt vor:*

- Kodi Starten und geöffnet lassen

Dann mit dem Windows Explorer/ES File Explorer zu dem oben angeführten Pfad gehen und den Ordner löschen

Zurück in Kodi kann nun der Wunschpfad eingetragen werden

Den genauen Speicherort (abhängig vom Betriebssystem) findet Ihr im Kapitel 5.3

**Lastship Serien Ordner & Filme Ordner zur Bibliothek hinzufügen**

**Serien**

*Gehe zu: *

 - Kategorie Videos-Dateien
 
   Videos hinzufügen 
 
   Videoquelle hinzufügen: klicke auf *Durchsuchen*

   Suche jetzt den oben angeführten Pfad für die Serien
  
   Dann gib im unteren Feld einen Namen ein und klick OK

*Inhalt festlegen:*

hier wird eingestellt, ob es eine Serie oder ein Film ist

*Dieser Ordner beinhaltet:*
wähle aus was du brauchst, z.B. Serien

*Bitte Informationsquelle wählen:*
The TVDB

*Einstellungen:*
Aktiviere Fanart: aktivieren
Sprache: de
Get rating from: The TVDB wählen

OK
Inhalt Scanning Einstellungen kann man alles deaktiviert lassen

**Filme**

*Gehe zu:*

- Kategorie Videos- Dateien

  Videos hinzufügen 

  Videoquelle hinzufügen: klicke auf *Durchsuchen*
   
  Suche jetzt den oben angeführten Pfad für Filme
  
  Dann gib im unteren Feld einen Namen ein und klick OK

*Inhalt festlegen:*

hier wird eingestellt, ob es eine Serie oder ein Film ist

*Dieser Ordner beinhaltet:*

wähle aus was du brauchst, z.B. Filme

*Bitte Informationsquelle wählen:*

The Movie Database

*Einstellungen:*

Verwende Original Titel: kann deaktiviert werden

Aktiviere Fanart: aktivieren

Aktiviere Trailer: wenn gewünscht, EIN

Sprache: de

Altersbewertung: de

Lade die Bewertung von: TMDb oder IMDb wählen

OK

*Inhalt Scanning Einstellungen:* 

Rekursives Scannen aktivieren

(damit die Unterordner ordentlich eingelesen werden)

Filme liegen in getrennten Ordnern, die dem Filmtitel entsprechen aktivieren

Fertig

Serien & Filme werden jetzt im Kodi Menü Serien bzw. Filme angezeigt

Solltet Ihr jetzt Eure Filme/Serien noch nicht sehen, dann das “Seitenmenü” (Optionen) öffnen und Bibliothek aktualisieren klicken, oder wie oben beschrieben

Wird die Bibliothek verwendet, ist die Hoster Anzeige nur als Dialog (kleines Fenster in der Bildschirm Mitte) möglich

Das liegt daran, dass es innerhalb der Bibliothek Navigation nicht möglich ist, dass Kodi ein Verzeichnis (Liste) öffnet

*Vorteil gegenüber Trakt?*

Der Vorteil der meisten ist einfach die Verwaltung in Kodi direkt

Trakt kann auch  mit der Bibliothek genutzt werden

**Lastship Bibliothek Ordner in das lokale Netzwerk (USB Stick am Router, Festplatte am Router)auslagern**

Es auch möglich, den Speicherort auf einen am Router angeschlossenen USB Stick oder USB Festplatte, festzulegen

Das ist vorallem dann zu empfehlen, wenn Ihr mit mehreren Kodis auf die Bibliothek zugreifen wollt

Wie solche Netzwerkfreigaben für Kodi funktionieren findet Ihr in der Kodi Anleitung: [Link](https://www.dropbox.com/s/vlaf0ap156267pr/Kodi_17_Anleitung.pdf?dl=0)

Es musst dann aber auf jedem Kodi, immer wenn Ihr was neues hinzugefügt habt, die Bibliothek aktualisiert werden

Wollt Ihr das auch nicht selbst machen, dann kann das Addon *Watchdog* verwendet werden 

Dieses Addon, aktualisiert einen von Euch festgelegten Pfad (z.B. am USB Stick der am Router hängt), automatisch zur lokalen Bibliothek

Es erkennt auch wenn Einträge gelöscht werden und aktualisiert auch das in der lokalen Bibliothek

Es ist sowohl in den Kodi- als auch in den Lastship-Einstellungen keine automatische Bibliothek-Aktualisierung eingestellt, das macht dann Watchdog

Es ist leider nicht möglich den Fortsetzungspunkt zu exportieren (ist nur möglich wenn Trakt + Trakt Addon verwendet werden)

Für den Export des "gesehen Status" benötigt Ihr ebenfalls ein eigenes Addon, wie z.B. *Watched List.* oder es wird, wie weiter oben beschrieben, die video.db selbst exportiert

Nach dem Watched List Konfiguriert wurde arbeitet es automatisch

Es legt eine eigene Datenbank für den gesehen Status an 

Der Speicherort für diese Datenbank kann frei gewählt werden, z.B. am USB Stick der am Router hängt. Somit habt Ihr den gesehen Status lokal im Netzwerk

Das Gute an WatchedList ist, dass das Addon optional an Dropbox angebunden werden kann

Einziger Nachteil: man darf nicht mehrere Geräte gleichzeitig betreiben, weil immer nur ein Kodi auf die Datei zugreifen darf

Eine Englische Beschreibung (kodi.wiki) zum Addon findet Ihr hier: [Link](http://kodi.wiki/view/Add-on:WatchedList)

**Trakt Verknüpfung zur Bibliothek hinzufügen:**

Als erstes muss ein Trakt Konto erstellt werden und dann in Lastship den Trakt API  (unter Konto) aktivieren

Dann wählt man den gewünschten Trakt Ordner (Filme,Serien usw.)aus

Über das Kontexmenü *"zur Bibliothek hinzufügen"* wählen (ein Fenster "Hinzufügen zur Bibliothek" wird angezeigt)

Im Anschluss öffnet  die entsprechende Kategorie in Kodi z.B. Serien

Solltet Ihr jetzt Eure Filme/Serien noch nicht sehen, dann das "Seitenmenü" (Optionen) öffnen und Bibliothek aktualisieren klicken

**Trakt gesehen Status/Fortsetzungspunkt in die Bibliothek importieren**

Um den aktuellen gesehen Status von Trakt zu erhalten, ist es notwendig das Addon Trakt (Scrobbler) zu installieren und entsprechend einrichten

Nach dem synchronisieren mittels Trakt Addon, wird der korrekte gesehen Status in der Bibliothek angezeigt

Wähle nun im Seitenmenü (Optionen)*"Bibliothek aktualisieren"* 

Es wird ein Fenster angezeigt ("Durchsuchen Serien/Filme mit ....). Wenn das fertig ist habt Ihr Eure Serien/Filme in der Bibliothek

Mittels Trakt Addon könnt Ihr ganz einfach den "gesehen Status" & den "Fortsetzungspunk" synchronisieren

Die Automatische Synchronisation kann in Lastship unter Allgemein - Trakt Bibliothek Automatische Synchronisierung eingestellt werden, entweder bei Kodi Start oder geplantes Update (nach Stunden)

## 2.12 Sortierung der gefundenen Links in der Ergebnisliste

Im folgendem wird versucht zu Erklären, wie die Ergebnisliste arbeitet

- Als erstes werden (falls vorhanden) lokale Dateien aus der Kodi-Library gelistet

- Danach werden werden die Links aufgelistet, in verschiedene Kategorien eingeteilt :

    1) 1080p        - Debrid Links
    2) 720p (HD)    - Debrid Links
    3) 1080p        - direkte Links
    4) 720p (HD)    - direkte Links
    5) SD / unbek.  - Debrid Links
    6) SD / unbek.  - direkte Links


Wenn die Einstellung "Nach Indexseiten sortieren" aktiv ist, werden innerhalb der einzelnen Kategorien die Ergebnisse alphabetisch nach Provider sortiert.

Das ergibt pro Kategorie und Provider jeweils eine Unter-Kategorie :

    1) 1080p        - Debrid Links
         - Premium-Provider a
         - Premium-Provider b
         - ...
    2) 720p (HD)    - Debrid Links
         - Premium-Provider a
         - ...
    3) 1080p        - direkte Links
         - Provider a
         - Provider b
         - ...
    4) 720p (HD)    - direkte Links
         - Provider a
         - ...
    5) SD / unbek.  - Debrid Links
         - Premium-Provider a
         - ...
    6) SD / unbek.  - direkte Links
         - Provider a
         - ...


Innerhalb dieser (Unter-)Kategorien wiederum werden die verschiedenen Hoster nach Zufall sortiert.

Die Prioritäts-Einstellungen im URLresolver haben also KEINE Auswirkung auf die Sortierung der Hoster
        3) 1080p        - direkte Links
         - Provider a
              - Hoster X
	      
              - Hoster W
	      
              - Hoster Z
	      
              - Hoster Y
	      
	      - Provider b
	      
              - Hoster Z
	      
              - Hoster X
	      
              - Hoster W
	      
              - Hoster Y
        
Das zufällige Mischen der Hoster-Reihenfolge ist erforderlich, um zu vermeiden dass eine einzelne Quelle die Zugriffe aller Autoplay-Nutzer tragen muss

Die Last soll hierdurch soweit möglich zwischen den verschiedenen Hostern aufgeteilt werden

# 3. Bekannte Probleme

## 3.1 Fehler bei der Installation

**Bei der Installation von Lastship erscheint folgende Fehlermeldung**

Installation fehlgeschlagen --> Installation der Abhängigen fehlgeschlagen

- Lösung: Deaktiviert alle Repositorys, welche Lastship/Placent/Incursion/Covenant anbieten 

- Danach Lastship aus der offiziellen Lastship Repo installieren und alles funktioniert

## 3.2 URL Resolver Fehler

Sollte dies der Fall sein, bitte den aktuellste Version des "URLResolver" über dier folgende Bezugsquellen beziehen:

[Download](https://github.com/lastship/lastship-common/tree/master/zips/script.module.urlresolver)

## 3.3 Beobachtungen und Fehler im Betrieb

**Premium Links werden übersprungen, normale Streams laufen, bzw. Ladekreis kurz sichtbar aber kein Stream**

Es kommt oft vor, dass Streams von Premium Anbietern (z.B. Premiumize, RealDebrid, AllDebrid, MegaDebrid usw.) nicht laufen

Entweder werden diese sofort übersprungen oder der Ladekreis ist kurz sichtbar aber kein Stream wird abgespielt

Normale Streams laufen hingegen ohne Probleme

Eine mögliche Lösung (die schon Erfolge gezeigt hat)ist folgende:

Im URLReslover die *Cache Funktion* auf AUS schalten

Erreichbar direkt über Lastship:

Werkzeuge - Konten-Debrid Dienste - URLResolver Einstellungen - Cache Funktion benutzen auf AUS stellen

Oder über Werkzeuge und ganz unten URLResolver Einstellungen

Eventuell noch *Cache Funktion zurücksetzen* klicken

**Fehlerhaftes Lastship Update verursacht Probleme**

Es kann vorkommen, dass ein Update Fehlerhaft ist und dann Probleme auftreten (z.B. alle Hoster werden übersprungen oder es kommt beim Start von Lastship eine Fehlermeldung usw.)

In diesem Fall müsst Ihr nicht warten, bis wir es beheben, sondern könnt selbst eine Version zurück springen

In Kodi: Addons - Addon Browser (Schachtel) - aus .zip Datei installieren - dann müsst Ihr den Kodipfad suchen (Kap.5.3)- addons - packages

Hier die alte plugin.video.lastship wählen und installieren

**Lastship ist sehr langsam**

Lastship ist als ganzes sehr langsam, im Menü und zum teile dauert es Minuten (z.B wenn man Traktlisten aufruft)

Kann an Trakt.tv liegen, wenn die Server wieder mal sehr langsam sind

Es gibt aber auch noch eine andere Möglichkeit:

Wenn ein Provider File auf eine falsche IP Adresse verweist 

Provider (source/de files ) werden an verschiedenen stellen initialisiert

Wenn es da irgendwo bei einem Webabruf hängt, hängen alle weiteren Lastship Operationen

*Bitte wie folgt testen:*  ALLE Provider aus dem Source Ordner entfernen/verschieben und einzeln nach und nach wieder zurück kopieren und testen wleche den Fehler verursacht


**URL Resolver Einstellungen werden nach Update gelöscht**

Lösung: die Option *"Cache-Funktion benutzen"* ausgeschaltet, befindet sich in den URL Resolver Einstellungen

Wenn das nicht helfen sollte, dann bitte wie folgt:

Da nach einem URL Resolver Update die Einstellungen (settings) weg sind, solltet Ihr diese vor einem Update sichern, damit Ihr nicht alles neu einrichten müsst

Nach dem Update, dann wieder in das Verzeichnis einfügen
Es ist nach dem URLResolver Update KEINE settings.xml vorhanden!!

Ihr findet die settings.xml hier: ....kodi/userdata/addon_data/script.module.urlresolver

**Probleme mit bs.to**

BS.to geht nicht mehr, da der API Key (Zugangspunkt Schlüssel) geändert wurde und wir keinen neuen bekommen

Ausserdem wurden Captcha eingeführt und diese lassen sich in Kodi (noch) nicht lösen

*Folgedes ist nicht mehr aktuell, bleibt aber vorerst als "Notiz" stehen:*

Laut Auskunft der Betreiber von BS.to, die sagen:

Dass bei ihnen bestimmte IP-Ranges als "sauber" eingestuft werden 

Bei Zugriff von einer dieser "sauberen" IPs wird kein Captcha angezeigt, bei den anderen, zu denen die meisten ausländischen gehören, schon

Die Betreiber der Site machen das, um Linkcrawler von anderen Index-Seiten abzuwehren, die die Streams auf ihrer eigenen Seite verlinken möchten

So soll die Verbreitung der Links und damit die Zahl der gemeldeten (und damit gelöschten) Files verringert werden.

Für Lastship-Anwender, die das Glück haben, eine "saubere" IP zu haben, funktioniert die aktuelle Version aus dem Repo

Für die anderen leider nicht

**Real Debrid (RD) Links werden mit VPN übersprungen/nicht angespielt**

Versuch es mal mit einem VPN-Server in Deinem Heimatland, damit sollte es funktionieren

Aus dem Ausland fragt RD ein Captcha ab, wenn Du Dich anmeldest. Deshalb überspringt Lastship die Links

(Eventuell TCP auf UDP umstellen)

**Lastship zeigt keine Filme mehr (mit Trakt Konto) in der Merkliste (Watchlist) an**

Es kann Zeitweise zu Problemen mit dem Trakt Konto kommen und da kann es dann passieren, dass eben nichts mehr angezeigt wird in der Merkliste (evetuell auch in andern Listen)

*Lösung*:

Lastship Cache zu löschen (Menüpunkt Werkzeuge)

Trakt Konto Verbindung trennen (disconnecten) --> Trakt Konto neu verbinden (connecten)

**Nach Film/Serien Auswahl werden wenig HD Anbieter angezeigt**

Wenn Ihr einen Film oder eine Serie auswählt, dann kann es sein, dass nur wenig HD/720P/1080P usw. Anbieter angezeigt werden

Das ist KEIN Fehler von Lastship

Der Fehler liegt hier bei Trakt bzw. deren Datenbank

*Lösung:* 

Einen Schritt zurück gehen und die Serie/ den Film ein zweites oder drittes mal Auswählen bis mehr HD Hoster angezeigt werden

**Suche liefert kein Ergebnis, Suche zeigt kein Ergebnis an**

Lastship findet eine Serie oder einen Film bei der Suche nicht,obwohl auf thetvdb die Infos vorhanden sind.

Ein Beispiele: Die Biene Maja 2012

*Wie kann ich die Serien in Lastship finden??*

Die Suche basiert auf Trakt.tv. Trakt nutzt thevdb & imdb Datenbank

Wenn auf Trakt.tv der Film oder die Serie gefunden wird,  findet es auch Lastship

Der Film oder die Serie kann dabei in der Datenbank auch einen Englischen Namen enthalten/haben

Das Beispiel Biene Maja:  wird gefunden wenn es "Maya" geschrieben wird

Auch wenn Trakt nicht genutzt wird in/mit Lastship, benutzt Lastship trotzdem die Suche von Trakt.tv

Des weiteren, könnt Ihr auf der Homepage von Trakt.tv, Filme&Serien selbst zur Datenbank hinzufügen/nachtragen, wenn diese nicht vorhanden sind

Dazu benötigt Ihr die Film oder Serien ID Nummer, welche Euch auf thevdb.com angezeigt wird

Am unteren Ende der Trakt Homepage, findet Ihr das Import Menü für Filme (Import Movie) und Serien (Import TV Show), hier müsst Ihr die ID Nummer eingeben

**Trakt watched Status & Lastship**

Folgendes Problem sollte eigentlich nicht mehr Auftreten

- einmal in Lastship "mit trakt angesehen" markierte Filme lassen sich nicht mehr als "mit trakt ungesehen" markieren und werden auf trakt.tv aber auch nicht als watched übernommen

- Staffeln in Serien lassen sich nicht einzeln als watched oder unwatched markieren

Die Markierung einer Staffel als "watched/unwatched" markiert immer gleich alle Staffeln

**Trakt arbeitet sehr langsam/Inhalte werden nur langsam geladen**

Das Trakt langsam lädt liegt leider am Trakt

Es gab keine Änderung an der Trakt-Integration, es liegt daher nicht an Lastship

Das Laden z.B. der Merkliste kann schon mal ein paar Minuten dauern

**Abbruch der Streams/Buffern der Streams während der Wiedergabe**

Gehört eigentlich nicht hier in diese Kategorie, da es kein Fehler von Lastship ist

Aber da es oft gefagt wird, bzw. öfters vorkommt steht es eben hier

Wenn der Stream an Kodi übergeben hat, ist die die Sache für Lastship durch/erledigt

Wenn Streams abbrechen/buffern oder ähnliches, ist das ein Problem von Kodi und nicht von Lastship

Was das verursacht müsste man genauer klären, eventuell hilft eine advancedsettings.xml

**Super Favoriten funktioniert nur teilweise mit Lastship**

Bei Filmen gibt es meistens kein Problem mit dem Addon SuperFavoriten

Bei Serien ist es jedoch so, dass diese in den SuperFavoriten Ordner integriert werden können, jedoch kann der Stream nicht abgespielt werden, es tut sich gar nichts

Mit einem kleinen Trick, behebt Ihr diese Problem. 

*Folgender Vorgang muss nach jedem Lastship Update erneut durchgeführt werden*

Navigiere zu folgendem Ordner: 

(Kap.4.2 steht der ganze Speicherpfad)

...../.kodi/addons/plugin.video.lastship/resources/lib/modules/control.py

Öffne die control.py 

Suche folgenden Eintrag
		 
		  def moderator():

Füge hier folgendes hinzu:

	'plugin.program.super.favourites'

sieht fertig dann so aus:

	def moderator():
    netloc = [urlparse.urlparse(sys.argv[0]).netloc, '', 'plugin.video.live.streamspro',
    'plugin.video.phstreams', 'plugin.video.cpstreams', 'plugin.video.tinklepad', 'plugin.video.metallic',
    'plugin.video.metalliq', 'plugin.program.super.favourites']

Speichern. Nun kann SuperFavoriten ohne Probleme mit Lastship genutzt werden

**Fehlermeldung: "Kein Stream verfügbar"**

Lastship greift bei der Suche, Film/Serienauswahl zuerst auf eine Filmdatenbank zu (IMDB), fragt diese nach Infos zum Film, zur Serie ab und zeigt diese dann an

In dieser Datenbank sind also nur Informationen zu Filmen/Serien gespeichert und hat noch nichts mit der Verfügbarkeit des Streams/Hoster zu tun

Daher kommt es immer wieder mal vor, dass z.B. die Episode einer Serie (in Deutsch) angezeigt wird und wenn der Stream gestarte werden soll,kommt die Fehlermeldung:

"In Lastship kein Stream verfügbar"

Das ist KEIN Fehler von & in Lastship!!

**Falsche HD/1080p Angaben bei Streams**

Das ist KEIN Fehler von & in Lastship

Einigen Hoster haben falsche Angaben zur Qualität (Auflösung) der Streams, sollte eigentlich nicht mehr vorkommen seit Update 3.1.0

Da steht dann neben dem Hoster HD/1080p obwohl es nur ein SD Stream ist.

Bekannte Hoster wo die Auflösung (Qualität) neben dem Stream meistens falsch ist,da diese keine HD/1080p anbieten:

Streamcloud 

Vidto 

Vidiz 

Flashx

**Fehlende Artworks (Serien/Filmcover)**

Kann verschieden Ursachen haben, z.B. weil unser TMDB-Key veraltet ist

Eine Lösung ist dann ein Update von uns

Ebenso kann auch folgendes sehr oft helfen, falls die Artworks nicht angezeigt werden:

1.plugin.video.lastship deinstallieren

2. Kann generell oft bei Artwork Problemen helfen:

Löschen des kompletten thumbnails Ordners (wird bei Kodi Neustart wieder neu angelegt):

...kodi/userdata/thumbnail

und löschen der Textures13.db:

...kodi/userdata/Database/Texture13.db

3.plugin.video.lastship neu installieren (eventuell vorher noch *Kodi* Cache löschen)

Bei neueren Artwork kann es helfen, sich bei Fanart.tv einen API-Key zu besorgen und den in den Konten-Einstellungen einzutragen

Noch besser dort einen Premium-acc anlegen, dann bekommt man die Bilder schneller

TitanSkin und Artwork Probleme sind bekann, liegt am TitanSkin

# 4. Fehlerbericht über Log-Datei


## 4.1. Allgemeines zur Log-Datei

In dem log File werden alle Aktivitäten/Programmabläufe von Kodi protokolliert und gespeichert

Wenn man nun Probleme mit Kodi hat, ist es sehr hilfreich, dieses Log File im Forum zu Posten

Nur so kann eine schnelle und Zielgerichtete Lösung erfolgen.


## 4.2 Speicherort der Log Datei

Den Speicherpfad von Kodi anzeigen lassen – Scroll weiter runter zum Punkt Debug_Logging und folgen den Beschreibungen.

Das ist immer vom Betriebssystem abhängig

Im Folgenden werden bekannte Ordnerstrukturen der jeweiligen Betriebssysteme aufgelistet

Anstelle von "xbmc" kann in den Ordnern auch "kodi" stehen

(die Ordnerstruktur kann jedoch auch leicht von dieser Anleitung abweichen):

- Windows XP
   - `Documents and Settings\<your_user_name>\Application Data\Kodi`
- Vista/Windows 7
    - `C:\Users\<your_user_name>/%APPDATA%/Roaming/Kodi/Kodi.log`
- Mac OS X
    - `/Users/<username>/Library/Logs/ oder`
    - `/Users/<your_user_name>/Library/Application Support/Kodi/userdata`
- iOS
    - `/private/var/mobile/Library/Preferences`
- Linux, OpenElec, Raspberry Pi 1-3
    - `$HOME/.kodi/temp/`
    - `$HOME/.kodi/userdata/temp/xbmc.log`
    - `$HOME/.kodi/userdata`
- Android
    - `/android/data/org.xbmc.Kodi/files/.kodi/temp`
    - `data/data/org.xbmc.Kodi/cache/temp`

Die Ordner sind meist versteckt und müssen sichtbar gemacht werden, im Windows Explorer oder auf Android mit dem ESDateiexplorer.

Das Log File kann am besten mit Notepad++  unter Windows oder gedit unter Linux betrachtet werden

Auch der normale Texteditor unter Windows geht, Notepad ist aber übersichtlicher

Auf Android einen Texteditor verwenden zum Betrachten

Übrigens die Kodi „log.old“ ist die Logdatei vom letzten Neustart/Crash. Also wenn man keine mehr erstellen kann, dann diese nehmen.


## 4.3. Erstellen und Hochladen der Log-Datei

Kodi hat Standardmäßig die beiden wichtigen Log Addons integriert (eines zum Lesen der Log, das andere zum Hochladen). 

Damit ist das Erstellen der Log Datei und Posten im Forum sehr viel einfacher

In Kodi gehe zu:

- Addons

- Suche

In die Zeile "log" ein und Klicks auf Fertig.

Folgende Addons auswählen und installieren diese:

Log Viewer für Kodi (nur zum Lesen der Log-Datei)

Kodi Log Uploader (zum Auslesen & Uploaden der Log-Datei)

Mit dem LogViewer kann man die Log Datei ansehen, mit dem LogUploaded das Log-File auf den angezeigten Homepage-Link hochladen, die Anweisungen der Anzeige befolgen

Bei der Installation eine E-Mail Adresse angeben. An diese wird dir dann nach dem LogUpload ein Link zur Log Datei geschickt.

Diesen Link im Forum Posten oder alles in einen Texteditor koperien, Die Datei speicherun und im Forum hochladen.

Debug-Logging (Kodi GUI):

Manchmal ist es gut das Debug Logging in Kodi zu aktivieren um noch mehr Informationen zu erhalten

(geht nur wenn, wenn es nicht schon in der advancedsettings.xml akttiviert wurde)

Folgendes Ausführen:

 Desktop-Optionen
 
- Einstellungen

- System

- Debugging

- "Debug-Logging aktivieren" anklicken

Fertig

Es wird nun am oberen Rand eine Statuszeile eingeblendet mit Infos, **Hier ist auch der Speicherort der Log-Datei zu sehen!**

Starte Kodi neu und öffne das Addon welches einen Fehler verursacht. Erstellen dann sofort eine Log-Datei (dann ist der Fehler leichter herauszulesen).

Das Debug-Logging kann im Anschluss wieder deaktiviert werden.

Unter dem Punkt  Komponentenspezifische Protokollierung kann man bei der Kategorie "Konfiguration der Komponentenspezifischen Protokollierung" noch Einstellen was alles im Debug-Log Protokolliert werden soll.


# 5. Phyton Dateien


## 5.1. Allgemeines zur .py-Datei

Eine .py Datei ist eigentlich eine Textdatei

Die Endung .py verweist auf die Programmiersprache Python, welche in Kodi zur Anwendung kommt.Diese .py Dateien werden in sämtlichen/den meisten Addons verwendet.
 
 
## 5.2 Bearbeiten einer .py-Datei

Manchmal werdet Ihr lesen z.B. Wechsel die .py Datei in dem Ordner „xyz“, oder ändere den Eintrag in Zeile 134.

Öffnen könnt Ihr die Datei mit vielen Programmen z.B. Notepad++ (Freeware) oder Texteditor. 

In Notepad werden Euch die Zeilen-Nummern angezeigt und ist somit übersichtlicher, aber es geht auch mit dem EditorMit Notepad++ könnt Ihr die .py Datei sofort öffnen und wieder speichern.

Bei Verwendung des Text-Editors müsst Ihr die Endung vorher von .py auf .txt ändern. 

Dann könnt Ihr die Datei öffnen und Änderungen vornehmen. 

Im Anschluss bitte „Speichern unter“ wählen und bei „Dateityp“ alle wählen, und wieder als .py Datei speichern


## 5.3 Speicherort der einzelnen Webseiten (.py Dateien)

In den folgenden Ordnern findet Ihr alle Addons von Kodi

Das Addon Lastship wird  unter plugin.video.lastship installiert

Die Index-Seiten .py Dateien findet Ihr unter ....kodi/addons/plugin.video.lastship/recources/lib/sources/de

- Android 
	- `/Android/data/org.xbmc.kodi/files/.kodi/addons/`
	- `/sdcard/Android/data/org.xbmc.kodi/files/.kodi/addons/`  (.kodi ist ein versteckter Ordner)
- iOS
	- `/private/var/mobile/Library/Preferences/Kodi/addons/`
- Linux 
	- `~/.kodi/addons/`
- Mac 
	- `/Users/<your_user_name>/Library/Application Support/Kodi/addons/`
- OpenELEC 
	- `/storage/.kodi/addons/`
- Windows
	- `C:\Users\BENUTZERNAME\AppData\Roaming\Kodi\addons`    (AppData ist ein versteckter Ordner)
