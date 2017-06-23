Biblio_reader
=============

Welcome! Biblio_reader is a literature parsing tool that compiles and analyzes publications matched by Google Scholar searches.
For publications found on Google Scholar between pages 1 and 99, it can do the following:
* Compile key information from each publication (such as article title, year, authors, journal title, URL, and citations)
* Write all key information into a CSV file
* Look for trends in journal fields, publication growth over the years, publication types, journal impact, citations, and more
* Find and display author information, including relationships between each author and attributed articles
* Help users find full-text PDFs for each publication 
* Subsequently analyze and categorize full text files for each PDF 
* Map author affiliations on Google Maps
* Facilitate manual publication review, including assigning articles to separate reviewers and analyzing their input
* Create a sortable table displaying publications and key information about each article

Navigation
----------
Biblio_reader has many submodules, and navigating them can be a bit intimidating. Hopefully this section helps you understand each section more comprehensively.

### manager.py

Manager.py is the utilities manager, and provides support for reading and writing files through the inputs, outputs, and working directory. It is also in charge of updating the main data CSV file with the update_data() method.

This is also where users can enter project-specific variables including marking which publications are connected to the original work of interest, and categories of search terms with regular expressions Google Scholar may have used to find them.

### [scholar](/scholar/README.md)

scholar.py is where the original Google Scholar results are compiled. (More in link)

### [biblio_reader](/biblio_reader/README.md)

### inputs

### outputs

### working

### table

