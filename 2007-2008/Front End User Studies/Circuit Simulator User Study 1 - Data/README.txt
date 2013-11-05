These data files were created when the Truth Table Recognizer
would return sketches that would not correctly save to file.  
The main bug causing this error was that the Truth Table 
Recognizer was not initializing all necessary XML attributes to 
some sketch elements like Shape and Substroke (e.g., the name, 
type, etc. fields are missing for some elements in these
XML files).  All *-notes.xml files may need to be converted before
they are opened.  This conversion might be as simple as deleting 
all the shapes in the sketch.  Conversion was not performed during 
Summer 2007 due to time constraints.  Paul Wais and Sara Sheehan 
have the most knowledge about issues with this dataset. 