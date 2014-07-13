  Moodle 2.3+ plugin: EasyOChem Marvinsketch Selection question type

INSTALLATION:

This will NOT work with Moodle 2.0 or older, since it uses the new
question API implemented in Moodle 2.1.

This is a Moodle question type. It should come as a self-contained 
"easyoselect" folder which should be placed inside the "question/type" folder
which already exists on your Moodle web server.

Once you have done that, visit your Moodle admin page - the database 
tables should automatically be upgraded to include an extra table for
the EasyOChem Mechanism question type.

You must download a recent copy of Marvinsketch from www.chemaxon.com 
(free for academic use) and intall it in folder named "marvin" at your web root.
Alternatively you could edit the php scripts if your marvin installation is elsewhere.


USAGE:

With the Marvin Sketch Selection question type the instructor draws a structure,
set of structures or reactions and selects certain objects (atoms, molecules etc).
The student must then select the same objects.  You can ask questions such as
"Select all chiral centers in the following structures?"  or Choose the nucleophile in the following reaction?
