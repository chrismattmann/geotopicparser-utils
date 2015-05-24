GeoTopicParser Utilities
========================
This repository contains Named Entity Recognition (NER) models for location data 
forked and augmented from the [Apache OpenNLP](http://opennlp.apache.org/) project,
trained against the [NSF Polar CyberInfrastructure](http://github.com/chrismattmann/trec-dd-polar)
data contributed to the NIST TREC Dynamic Domain Working Group. 

In addition, a custom MIME type definition for the [Tika GeoTopicParser](https://wiki.apache.org/tika/GeoTopicParser)
is provided so that *.geot files can be parsed using the GeoTopicParser. *.geot flies are just text/plain files with
text that includes location information.

Finally, a sample set of *.geot files are provided, currently there exists one from the Polar domain.

Questions, comments?
===================
Send them to [Chris A. Mattmann](mailto:chris.a.mattmann@jpl.nasa.gov).

Contributors
============
* Yun Li, USC
* Chris A. Mattmann, JPL

Credits
=======
This project began as the [CSCI 572](http://sunset.usc.edu/classes/cs572_2015/) 
project of [Yun Li](https://github.com/AranyaLi) on the NSF Polar CyberInfrastructure
project at USC under the supervision of Chris Mattmann. You can find Yun's original
code base [here](https://github.com/AranyaLi/GeoParsingNSF).

This work was sponsored by the [National Science Foundation](http://www.nsf.gov/) 
under funded projects 
[PLR-1348450](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1348450&HistoricalAwards=false) 
and [PLR-144562](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1445624&HistoricalAwards=false).


License
=======
[Apache License, version 2](http://www.apache.org/licenses/LICENSE-2.0)