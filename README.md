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

License
=======
[Apache License, version 2](http://www.apache.org/licenses/LICENSE-2.0)