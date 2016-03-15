# COMP317Notes
Notes for the University of Liverpool module
'Semantics of Programming Languages'

## Basic Info
This repository is created as a collection of my notes on the module.  This
repository should be updated about once a week within the realms of Thursday to
Sunday.  I will probably begin with writing .org files, then move the 
information into .tex files to compile the info into PDF.  Links to the
[Module Overview](https://www.csc.liv.ac.uk/teaching/modules/module.php?code=comp317)
and the [Main page](http://cgi.csc.liv.ac.uk/~grant/Teaching/COMP317/).

EDIT: This seems to be a lie and slightly ambitious but I'll get around to
writing the notes up as and when I can, I promise.  As of 15/03/2016 I'm about
6 lectures (2 weeks) behind.

## Accessing this Information
You can obtain this repository's information in a variety of different ways:

1. If you have 'git' installed, you can use the command
'git clone https://github.com/Chuddington/COMP317Notes.git' to create a copy
of the 'COMP317Notes' folder (Base Directory) where your command 
prompt/terminal currently is.  If you are using a GUI client for git, such as
'Git for Windows,' you can use the clone option and copy the link in the box it
provides and it will download it just the same.  The command 'git pull' when
within the 'COMP317Notes' folder will update your local copy if required, or
your GUI will inform you if your copy is out of date.

2. You can download an archive of the repository near the top-right of the
directory explorer thing whilst on the repository.  If you can't find it,
[don't despair:](https://github.com/Chuddington/COMP317Notes/archive/master.zip)
It will be the most recent version of what has been created, for those that
like your information to be as 'bleeding edge' as it can be.

3. I have now made tags for when a week's worth of notes has been written up.
You'll find them in the 'releases' section.  The versioning system will be
'0.X' where X = the week's notes that have been completed in .org files.  Once
all of the notes have been written up, the versioning will move onto '1.X'
with X standing for the same thing but for .tex files.  Finally, version
'2.0' will be when a PDF file for all weeks hava been compiled from the .tex
files, as it doesn't make sense for me to make sub-versions for me just
compiling the .tex files.

4. You can view it online.  If you do, it is best that you view the .org files
in their 'raw' form - whilst github knows the basics of formatting .org files,
it does not account for some of the quirks I have in showing the information
more easily for those using simple text editors.  As such, some of the examples
which use sub-scripting may show up incorrectly and will attach the subscript
sections to the end of the above lines, instead of keeping the formatting.

## File Types
### Org
If you have [Emacs](https://www.gnu.org/software/emacs/#Obtaining), .org files 
will probably be your favoured method of reading the information, due to it's
LaTeX math mode capabilities and it's ability to grow/shrink topics.  Of
course, if you have another editor that is capable of reading .org files with
all of it's features (if such a thing exists), then by all means use that.  
.org files are simple files otherwise and can be read in most text editors just
like a plain .txt file.

### PDF
If you want to read the information on something a little more portable than a
computer, the compiled PDF files will be of more use to you.

### LaTeX
You can also download this respository and compile the .tex files yourself - 
this would be useful if you plan on changing wording or spelling, or if you
wish to have the compiled files become a different filetype, such as DjVu.

## Making Changes
If you do make changes, send this information to me and I'll add it in if I
think it's better than my current explanations.  By better I mean 'easier to
understand for someone who has paid little attention to the subject.'  Examples
made clearer would be a good reason for me to update the repository.

I'd like this to be a collaborative side-thing so that students are able to 
understand this module through a combined effort.  Therefore I ask that you 
keep to a couple of things whilst you are adding your two cents:

1. Keep all .org and .tex files to a limit of 80 characters wide.  Most decent
text editors have a line count and a character count somewhere on the GUI, 
usually the bottom.  This is purely so the source is easier to read when you 
have your editor to one side (Windows edge-snapping, tiling window managers 
etc.)

2. Use spaces instead of tabs.  Some people prefer using tabs for indenting
their code/text and spaces for alignment.  My problem with tabs though is that
people have them on different strengths (2, 4, 8 spaces wide).  So if I write
things for this repository based on my preference of a 2-space indent using
tabs, for other people it may no longer follow the guideline of having it look 
80 characters wide (due to having their indent size on 4 spaces, or 8).
This makes the formatting not look pleasant whilst edge-snapping."By catering
to no-one, I'm catering to everyone."  There are methods for many text editors
to allow swapping tab to an amount of spaces - look it up for your editor if
you are unsure whether you have tabs-to-spaces on or not

3. Keep consistent formatting throughout the file.  I don't mind different
styles across multiple files, but try and keep to the current style if you are
adding anything to an existing file.  So long as the above guidelines are 
followed, everything else is a matter of preference.

## Additional Information
### Maude
The later sections will utilise 
[Maude](https://en.wikipedia.org/wiki/Maude_system), a Logic programming 
language which can be used to model various things.  I'm not doing it justice,
but [here](http://maude.cs.illinois.edu/w/index.php?title=The_Maude_System) is
the home page for Maude.

#### Downloading Maude
* [For Linux/Mac OS X](http://maude.cs.illinois.edu/w/index.php?title=Maude_download_and_installation)

* [For Windows](http://moment.dsic.upv.es/component/option,com_docman/task,cat_view/gid,18/Itemid,41/).
As of this writing, Maude for Windows seems to be one minor version behind
(2.6 instead of 2.7) so it might be an idea to compile it yourself.  I've not
tested but 
[follow these instructions](http://maude.cs.uiuc.edu/download/windows.html) to
compile on windows, using [Cygwin](https://www.cygwin.com/).

* Extending maude, known as 'Full Maude' is also available and is platform
independant - you can get it
[here](http://maude.cs.illinois.edu/w/index.php?title=Maude_download_and_installation).  It does require that you have 'Core Maude' installed though.
