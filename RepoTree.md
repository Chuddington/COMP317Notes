# Description of current folder structure

## Overview of the Major changes

- Some new folders have been created / merged together in order to separate
  the different types of content available.  To keep the folder names clean
  in the base directory, they are lower case and are named after the filetypes
  that will be within the folder.  As an example, the 'org' folder we all know
  and love will have all the .org files which contain my notes.

- The .org files, instead of going by the weeks in which the notes are from,
  instead have the lecture numbers within the file name, so you do not need to
  open the files in order to know which lectures the information is relevant
  for.

- The folders 'pastExams,' 'problemSheets' and 'webPagePDFs' have now moved.
  They are within the new 'pdf' folder when you are within the base directory.
  It made sense to store all of the pdf files within the same 'main folder.'

- A second new folder is now here - the 'ogg' folder.  .ogg files are a
  container file extension which usually house audio coded in the 'Vorbis'
  format.  If I ever get around to transcoding the audio / one-case-of-video
  that the Lecturer has recorded, It will probably be in the .ogg format.
  There are many programs that can allow you to listen to .ogg files, but
  by default 'Windows Media Player' and 'iTunes' do not (for vorbis-encoded
  audio, at least - I'm unsure about 'opus').  If you need help in running the
  .ogg files that may not even be here, then
  [This is the site for you.](http://www.vorbis.com/)

## Folder Structure
### [Ogg](ogg/)
- Will contain the audio from any lectures that have been recorded

- the [lectureList](ogg/lectureList) file contains hard links to the source
  of the audio, using your browser's default music player instead of a flash
  based plugin from the University streaming website or the Lecturer's website
  (which is just the embedded form of the audio from the streaming site
  anyway).
  
  - This allows you to download the files, something you cannot do
    when using the university's audio player.

### [Org](org/)
- The function is the same as before; to store my hand-written notes and to be
  the template for my LaTeX files.

- Naming convention has changed - Instead of 'weekX.org,' they are now
  'lecture-X-Y-Z.org.'  This allows people to fill in gaps with their 
  information without having to check the contents for the right org file.

- Github tags/releases will still follow the same naming convention, as I
  don't think anyone will download anything other than the most recent version
  anyway.

### [Pdf](pdf/)
- This is the folder with the most amount of files within it's
  sub-directories.
- There is a 'fileInfo' file which has information about the content within 
  the folder it is found in - think of them as indexes.
  
  1. [backgroundReading](pdf/backgroundReading/) is for anything related to 
     the module but may not necessarily be of use to anyone.  This includes 
     research papers and general information, such as an Overview of 
     Denotational Semantics.  This was originally called 'webPagePDFs' in the 
     base directory.
  
  2. [lectureSummary](pdf/lectureSummary/) contains a general overview of what 
     was covered within the lecture.  This is the lecturer's equivalent of my 
     .org notes.
     
  3. [orgNotes](pdf/orgNotes) are the final form of the notes initially 
     written within the .org files, hence the name of the folder.  Don't 
     expect these to be readily available any time soon.
     
  4. [pastExams](pdf/pastExams/) does exactly what it says on the tin.  
     Contains past exam papers that are for this module.
     
  5. [problemSheets](pdf/problemSheets/) house the weekly problems which are 
     given to us.  When available, this folder also contains the solutions, so 
     you can see where you may have gone wrong.

### [TeX](tex/)
- the .tex files that will eventually be found within are the intermediate
  stage of my notes - with the .pdf files being the final format that I will
  make.
- I'll start doing these .tex files when I have finished writing the
  .org files, otherwise it's just too much work when you include the other
  things I have to do.