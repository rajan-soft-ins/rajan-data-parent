# Spring Data Build Infrastructure

This repository contains common infrastructure to be used by Rajan Data modules that build with Maven.

It consists of the pre-configure core dependencies, properties, reference documentation generation and most important of 
all the appropriate distribution assembly.

## Project setup

If the client project is a project consisting of a single project only all that needs to be done is declaring the parent
project:

```
<parent>
	<groupId>com.rajanframework.data</groupId>
	<artifactId>rajan-data-parent</artifactId>
	<version>${last-release-version}</version>
</parent>
```


## License

Rajan Data Parent is Open Source software released under the Apache 2.0 license.
