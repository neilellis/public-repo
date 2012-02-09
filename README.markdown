Maven repository
================

Configuration
-------------

To add this repository to your Maven project, add the following lines to your `pom.xml` or `settings.xml` file.

### Dependency repository

	<repositories>
	  <repository>
	    <id>public-releases</id>
	    <url>https://github.com/neilellis/public-repo/raw/master/releases</url>
	  </repository>
	  <repository>
	    <id>public-snapshots</id>
	    <url>https://github.com/neilellis/public-repo/raw/master/snapshots</url>
	  </repository>
	</repositories>

### Plugin repository

	<pluginRepositories>
	  <pluginRepository>
	    <id>public-plugin-releases</id>
	    <url>https://github.com/neilellis/public-repo/raw/master/releases</url>
	  </pluginRepository>
	  <pluginRepository>
	    <id>public-plugin-snapshots</id>
	    <url>https://github.com/neilellis/public-repo/raw/master/snapshots</url>
	  </pluginRepository>
	</pluginRepositories>
