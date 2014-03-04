# CCU-IO.ScriptGUI
## Version 0.55

CCU-IO.ScriptGUI ist ein Visueller Script builder mit dem es möglich ist Scripte für CCU.IO zu erstellen, zu bearbeiten und zu testen.


## Todo/Roadmap



### 0.6
* Erstellen von Multi/Gewerk Triggerbausteinen ( A. Trigger) incl. Compiler einbindung

### 0.7
* Mode umschaltung GUI/EDIT

### 0.8
* Erstellen Testumgebung (Live Test)
* PI Regler
* PWM Baustein
* Zähler Baustein
* Math Bausteine
* Editor setup Dialog
* FBS Min
* FBS Max
* FBS Summe
* FBS Mittelwert
* Schleifen

### 0.9
* Druck formulare
* Mehr FBS
* Doku
* Beispiele
* Videos
* Translate Deutsch\Englisch
* Bugfixs
* Libs min.

### 1.0

## Changelog

### 0.60
* Add Grid
* Einige umstellung auf Flex Box (CSS)
* Größenanpassung aller Bausteine ans Grid
* Hinzufügen Listenauswahl (HM_Selckt_Dialog)
* FBS Dragging auf ThreeDubMedia lib umgestellt
* MBS Dragging auf ThreeDubMedia lib umgestellt
* Einige Repaints angepasst
* Umbau das HM Selekt Dialogs zur Jquery id_select function
* Dashui HM_Select wird nicht mehr unterstützt
* Komma getränte (oder) Suche im id_select für Type
* id_select combo boxen hinzugefügt
* Add Shortcut "Entf"
* Scrollbar auf jquery_perfect_scrollbar umgestellt und an Jquery UI Themes angepasst
* Umstellung auf jquery UI Themes 1.10.4 und JQuery 1.11.0
* Umstellung auf jsPlumb 1.6.0 und nutzung mehrerer scopes
* MBS CCU.IO Object persident
* MBS Script Object hinzugefügt
* MBS Local Var and Local Var seleckt
* FBS Local Get & Set hinzugefügt
* Autoformat bei Scriptvorschau
* Bug fix Programm Boxen können nicht mehr kleiner als ihr Inhalt gemacht werden

* Expert FBS mit Editor hinzugefügt mit:
    - Autocomplete
    - Format selction
    - ID select
    - Groupes select
    - Device select



* Live-Test (mit Debug Function hinzugefügt)


### 0.58
* FBS Wenn
* FBS Next 1
* Bug Fix leading zero on FBS Time
* Bug Fix Numbers of FBS Target connections
* Bug Fix Kommentar autosize

### 0.57.1
* Bug Fix Add Delay (Safari)

### 0.57
* Autosize Textarea for FBS String & Komex
* Add/Remove delay for MBS connections
* Add FBS Next

### 0.56
* Add FBS E-Mail
* Better Multiselect for FBS and MBS !!!
* Add Rename Program

### 0.55
* Add FBS Verketten
* Change FBS Zeit ( 10 Stellen)

### 0.54
* Working on SVG Files
* Add FBS Zeit
* Add Trigger Start

### 0.53.1
* Bugfix on FBS String

### 0.53
* PNG -> SVG
* Bugfix Drag to PRG
* Add MBS CCU.IO Object
* Add FBS Text
* Some Changes and Adds on "FBS Trigger Daten"
* Bugfix on HM Select Dialog

### 0.52
* Trigger VAL
* New HM Select Dialog (now Working)
* Singel Trigger preview change to SVG

### 0.51.2
* Bufgfix on Quick Help

### 0.51
* Astro Trigger
* New HM Select Dialog (nonWorking)
* Bugfixes

### 0.50
* Links zum Youtube Kanal
* Add Demo Licht

### 0.49
* Add io-addon.json

### 0.48
* Add Trigger --

### 0.47
* Kommentar Schrift und Hintergrundfarbe
* Add Script Lösch Dialog

### 0.46
* Add Trigger EQ
* Add Trigger NE
* Add Trigger GT
* Add Trigger GE
* Add Trigger LT
* Add Trigger LE

### 0.45
* Add Kommentraflächen

### 0.44
* Add Trigger Zyklus M
* Bugfixes

### 0.43
* Add CCU.IO LOG

### 0.42
* Add Trigger Zeit

### 0.41
* Compiler hmid bugfix

### 0.40

* Add Programmboxen
* Add jsPlumb instanzen
* Add Trigger Daten
* Add Quick Help
* Splitten der Bausteine in FBS & MBS
* Add Code Mirror

* Überarbeitung Drag&Drop
* Überarbeitung Select
* Überarbeitung "Make Struck"
* Überarbeitung Compiler
* Überarbeitung PRG Datenstrucktur
* Überarbeitung Load/Save

### 0.32
* (GermanBluefox) Use authentication

### 0.31
* Erstellen Script "Compiler"
* Tooltip Iconbar

### 0.30
* Trigger valNe


### 0.23
* Öffnen Dialog mit Datei löschen
* Save Dialog mit Datei löschen
* Anzeige Dateiname im Menu

### 0.22
* Hochzeit mit CCU.IO
* Offline ohne CCU.IO mit Daten aus sim-Store

### 0.21
* Übernahme HM_select aus DashUI

### 0.1
* Herstellung der Editor Grundfunktionen
* Grafischer aufbau
* Themes
* Menu
* Iconbar
* Contextmenue
* Toolbox
* Local Save/Open
* FBS anordnen
* Multi Drag


## In CCU-IO.ScripGUI verwendete Software

* jQuery http://jquery.com/
* CanJS http://canjs.com/
* lostorage.js https://github.com/js-coder/loStorage.js
* jQuery UI http://jqueryui.com/
* jsPlumb https://github.com/sporritt/jsplumb/
* jQuery ContextMenu http://medialize.github.com/jQuery-contextMenu/
* jQuery Mousewheel http://brandon.aaron.sh
* jQuery resize http://benalman.com/projects/jquery-resize-plugin/
* jQuery CodeMirror http://codemirror.net/



## Copyright, Lizenz, Bedingungen

CCU-IO.ScripGUI
http://github.com/smiling-Jack/CCU-IO.ScriptGUI

Copyright (c) 2013 Steffen Schorling http://github.com/smiling-Jack

MIT Lizenz (MIT)

Hiermit wird unentgeltlich, jeder Person, die eine Kopie der Software und der zugehörigen Dokumentationen (die
"Software") erhält, die Erlaubnis erteilt, sie uneingeschränkt zu benutzen, inklusive und ohne Ausnahme, dem Recht,
sie zu verwenden, kopieren, ändern, fusionieren, verlegen, verbreiten, unterlizenzieren und/oder zu verkaufen, und

Personen, die diese Software erhalten, diese Rechte zu geben, unter den folgenden Bedingungen:

Der obige Urheberrechtsvermerk und dieser Erlaubnisvermerk sind in allen Kopien oder Teilkopien der Software beizulegen.

DIE SOFTWARE WIRD OHNE JEDE AUSDRÜCKLICHE ODER IMPLIZIERTE GARANTIE BEREITGESTELLT, EINSCHLIESSLICH DER GARANTIE ZUR
BENUTZUNG FÜR DEN VORGESEHENEN ODER EINEM BESTIMMTEN ZWECK SOWIE JEGLICHER RECHTSVERLETZUNG, JEDOCH NICHT DARAUF
BESCHRÜNKT. IN KEINEM FALL SIND DIE AUTOREN ODER COPYRIGHTINHABER FÜR JEGLICHEN SCHADEN ODER SONSTIGE ANSPRÜCHE
HAFTBAR ZU MACHEN, OB INFOLGE DER ERFÜLLUNG EINES VERTRAGES, EINES DELIKTES ODER ANDERS IM ZUSAMMENHANG MIT DER
SOFTWARE ODER SONSTIGER VERWENDUNG DER SOFTWARE ENTSTANDEN.


HomeMatic und das HomeMatic Logo sind eingetragene Warenzeichen der eQ-3 AG
