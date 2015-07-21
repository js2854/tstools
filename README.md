# tstools
Automatically exported from code.google.com/p/tstools

This is a set of cross-platform command line tools for working with MPEG data.

The emphasis is on relatively simple tools which concentrate on MPEG (H.264 and H.262) data packaged according to H.222 (i.e., TS or PS), with a particular interest in checking for conformance.

Transport Stream (TS) is typically used for distribution of cable and satellite data. Program Stream (PS) is typically used to store data on DVDs.

The tools are focussed on:

Quick reporting of useful data (tsinfo, stream_type)
Giving a quick overview of the entities in the stream (esdots, psdots)
Reporting on TS packets (tsreport) or ES units/frames/fields (esreport)
Simple manipulation of stream data (es2ts, esfilter, esreverse, esmerge, ts2es)
Streaming of data, possibly with introduced errors (tsplay)

NB: This is the new home of the tstools project, previously at <http://tstools.berlios.de/>. Further development will occur here.
