mothur_krona_XML.py: A script converting mothur's taxonomy summaries into Krona-compatible XML files.

**Requirements**

 - [Mothur][1] (tested with 1.32.1)
 - [Python][2] 2.x (tested with 2.7.5)
 - [lxml][3] (tested with 3.2.3)
 - [Krona][4] (tested with 2.4)

**Usage**

mothur_krona_XML.py /path/to/tax.summary > output.xml

ktImportXML output.xml


  [1]: http://www.mothur.org/ "Mothur"
  [2]: http://www.python.org/ "Python"
  [3]: http://lxml.de/ "lxml"
  [4]: https://sourceforge.net/p/krona/home/krona/ "Krona"