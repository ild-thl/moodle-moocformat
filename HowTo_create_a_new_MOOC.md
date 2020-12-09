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
* Gearwheel in the upper right > Edit settings
  * Appearance > Force theme: moocster
  * Save and display
* Gearwheel in the upper right > Turn editing on (if not done already)
* Gearwheel in the right near "New MOOC" > Configure New MOOC block
  * Blocktitle: used as header for the course (Course name)
  * ID for the general discussion forum (from url in section 0)
  * ID of the directoy with the chapter images (from url in section 0)
  * ID of the textpage with the social media content (from url in section 0)
  * Chapter options:
    * `name=Kapitel 1;lections=3;enabled=true;img=digi1.jpg`
    * `name=Kapitel 2;lections=5;enabled=false;img=digin.jpg`
    * `name=Kapitel 3;lections=5;enabled=hidden;img=digix.jpg`
  * Save changes
* Gearwheel in the upper right > More... > Users > Enrolment methods
  * Add method: Auto Enrol
  * Custom Label: Automatische Einschreibung
  * Show more... (then scroll up a bit)
  * Enable self unenrol: Yes
  * Add method / Save changes
  * Disable for the moment (click on eye), enable if course has startet
* Add badges
* Gearwheel in the upper right > Turn editing off
## ildmeta ##
* TODO
