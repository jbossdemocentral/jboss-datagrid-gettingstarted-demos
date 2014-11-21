MODULE1-DEMO
===================================
**Author:** Thomas Qvarnström, tqvarnst@redhat.com   
**Level:** Beginner   
**Technologies:** In-memory datagrid   
**Summary:** A simple demo to show how easy it is to implement CRUD operations using JBoss Data Grid.   
**Prerequisites:** Java 1.6+, Maven     
**Target Product:** JBoss Data Grid     
**Product Version:** JBoss Data Grid 6.3   
**Slides** <http://jbossevangelist.slides.com/tqvarnst/jdg-startkit-module-1--2#/>

What is it?
-----------
A simple demo to show how easy it is to implement CRUD operations using JBoss Data Grid.

System requirements
-------------------
Java 1.6+, Maven 

How to Build and Deploy the Demo
--------------------------------
Note! This demos is preferably run directly in an IDE like Eclipse or JBoss Developer Studio. It is however possible to build and run from command line.

		$ mvn package
		
How to run
----------

		$ mvn exec:java -Dexec.mainClass=Demo1
