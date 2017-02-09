# Maven private repository#

Para utilizar este repositório, adicione no pom:

```
#!xml
<repositories>
	<repository>
		<id>itsstecnologia-repo</id>
		<name>Repository for ITSS private libs</name>
		<url>https://bitbucket.org/itssmultiplataforma/mvn-repo/raw/master/repository/</url>
	</repository>
</repositories>
```

## Dependências disponíveis##
### PRETTY-TOOLS-JDDE ###

```
#!xml
<dependency>
	<groupId>pretty-tools-JDDE</groupId>
	<artifactId>pretty-tools-JDDE</artifactId>
	<version>2.0.3</version>
</dependency>
```
### SAP-JCO ###

```
#!xml
<dependency>
	<groupId>com.sap</groupId>
	<artifactId>sap-jco</artifactId>
	<version>3.0.9</version>
</dependency>
```
### ALL Parent ###

```
#!xml
<dependency>
	<groupId>br.com.zurcs</groupId>
	<artifactId>all-parent</artifactId>
	<version>1.0.0</version>
</dependency>

### COMMONS UTIL ###

```
#!xml
<dependency>
	<groupId>br.com.zurcs.utilitario</groupId>
	<artifactId>commons-util</artifactId>
	<version>1.0.0</version>
</dependency>
```

### ARQUITETURA BASE ###

```
#!xml
<dependency>
	<groupId>br.com.zurcs</groupId>
	<artifactId>arquitetura-base</artifactId>
	<version>1.0.0</version>
</dependency>
```
