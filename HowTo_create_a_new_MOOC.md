# How to create a new MOOC #

## Create course ##
* Login to your Moodle as admin
* Site administration > Courses > Restore course
* Import a backup file (https://github.com/ild-thl/moodle-moocformat/blob/main/TemplateNewMOOC.mbz): use drag & drop to upload file and click button „restore“
* Continue
* Restore as a new course, Select a category, Continue
* Next
* Change Course name and Course short name, Next
* Perform restre, Next
## Configure course ##
* Zahnrad oben rechts > Einstellungen bearbeiten
  * Darstellung > Design festlegen: moocster
  * Speichern und anzeigen
* Zahnrad oben rechts > Bearbeiten einschalten (falls noch nicht eingeschaltet)
* Block "New MOOC" konfigurieren (Klick rechts auf Zahnrädchen neben "New MOOC")
  * Blocktitel: wird überall im Kurs als Überschrift angezeigt (Kursname)
  * ID Diskussionsforum (aus URL in Section 0)
  * ID Kapitelbildverzeichnis (aus URL in Section 0)
  * ID Social Media-Textseite (aus URL in Section 0)
  * Kapitelkonfiguration:
    * `name=Kapitel 1;lections=3;enabled=true;img=digi1.jpg`
    * `name=Kapitel 2;lections=5;enabled=false;img=digin.jpg`
    * `name=Kapitel 3;lections=5;enabled=hidden;img=digix.jpg`
* Zahnrad oben rechts > Mehr ... > Nutzer/innen im Block Einstellungen: Kurs-Administration > Nutzer/innen > Einschreibemethoden
  * Methode hinzufügen: Auto Enrol
  * Custom Label: Automatische Einschreibung
  * Mehr anzeigen ... (anschließend etwas nach oben scrollen)
  * Enable self unenrol: Ja
  * Methode hinzufügen
  * vorerst deaktivieren (Klick auf das Augensymbol), sollte erst aktiviert werden, wenn der Kurs offiziell für Teilnehmer/innen geöffnet ist
* Badges anlegen
* Zahnrad oben rechts > Bearbeiten ausschalten
## ildmeta ##
* TODO
