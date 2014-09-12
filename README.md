ElasticSearchOSGI
=================

The bundle used in compiling the ElasticSearch Jasper Plugin. This small
script creates a jar file that can then be added to your Eclipse workspace
as an OSGI Plugin. 

This jar file will be required to compile the ElasticSearch Jaspersoft
Studio plugin.

How to create the jar
---------------------

First of all you will need to download and copy in the **lib** directory
the following jars:

 - elasticsearch-1.1.2.jar
 - lucene-analyzers-common-4.7.2.jar
 - lucene-codecs-4.7.2.jar
 - lucene-core-4.7.2.jar
 - lucene-grouping-4.7.2.jar
 - lucene-highlighter-4.7.2.jar
 - lucene-join-4.7.2.jar
 - lucene-memory-4.7.2.jar
 - lucene-misc-4.7.2.jar
 - lucene-queries-4.7.2.jar
 - lucene-queryparser-4.7.2.jar
 - lucene-sandbox-4.7.2.jar
 - lucene-spatial-4.7.2.jar
 - lucene-suggest-4.7.2.jar
 - spatial4j-0.4.1.jar

At this point you can simply run:

  ./mkbundle

and you should find yourself with a shiny ** org.elasticsearch.osgi-1.1.2-bundle.jar ** library that you
can import into your Eclipse workspace as a plugin to satisfy the
dependency in the ElasticJasper plugin.


