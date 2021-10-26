# Moodle MOOC format documentation #
Documentation of everything we need to set up a moodle as MOOC plattform
* Moodle plugins
* Moodle desgin
* Moodle configuration
* Course templates
## Moodle plugins ##
We need the following plugins to be installed in our Moodle
(for file drag'n drop installation follow the path in Moodles backend in front of _ )
* block_ild_chosencourses (in Moodle backend in blocks)
* block_ildmetaselect
* block_oc_course_footer
* block_oc_mooc_nav
* block_online_users_map
* format_fntabs (in Moodle backend in course/format)
  * use the modified fntabs plugin from futurlearnlab 
* theme_moocster
* enrol_autoenrol
* mod_hvp
* local_ildhvp (https://github.com/oncampus/moodle_local_ildhvp)
* local_ildmeta
## Moodle design ##
TODO
## Moodle configuration ##
* Hide course sections in navigation
  * mymoodle.de/admin/search.php?query=linkcoursesections
## Course templates ##
To create a new MOOC from a course template use this step by step turorial [How to create a new MOOC](https://github.com/ild-thl/moodle-moocformat/blob/main/HowTo_create_a_new_MOOC.md).  
Use this Moodle course backup as template: [TemplateNewMOOC.mbz](https://github.com/ild-thl/moodle-moocformat/blob/main/TemplateNewMOOC.mbz).
