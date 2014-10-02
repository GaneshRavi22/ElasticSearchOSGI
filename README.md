ElasticSearchOSGI
=================

The bundle used in compiling the ElasticSearch Jasper Plugin. This small
script creates a jar file that can then be added to your Eclipse workspace
as an OSGI Plugin. 

This jar file will be required to compile the ElasticSearch Jaspersoft
Studio plugin.

How to create the jar
---------------------

You can create the OSGI bundle using Maven. The default phase is already set, so you just
need to run:

	mvn

and you should find yourself with a shiny **org.elasticsearch.osgi-1.1.2-bundle.jar** library that you
can import into your Eclipse workspace as a plugin to satisfy the dependency in the ElasticJasper plugin.

If you need to cleanup the directory from old libraries and and old version of the bundle just run:

	mvn clean

