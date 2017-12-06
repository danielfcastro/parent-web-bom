parent-web-bom
========================

A Bill of Materials - within Maven Context - is a way to list a set of libraries that are common to your project environment inside a pom file and set it as a parent for others.  It is also possible to inherit a POM from another POM giving more control over the dependencies.

Usage
-----
Just insert the parent tag below inside your pom file.
The relativePath is not required but may be in handy if your project is using a pom that lies inside a closed eclipse project.


	<parent>
		<artifactId>parent-web-bom</artifactId>
		<version>1.0</version>
		<relativePath>../parent-web-bom</relativePath>
	</parent>