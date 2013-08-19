# FHIR Maven Package

Packages latest java zip file extracted from the [HL7 FHIR](http://www.hl7.org/implement/standards/fhir/index.htm) java
[Download page](http://www.hl7.org/implement/standards/fhir/downloads.htm) into a jar.

    <dependency>
        <groupId>org.hl7</groupId>
        <artifactId>fhir</artifactId>
        <version>v0.11-1711</version>
    </dependency>
    
To get it from my repo, add this to your repositories:

    <repository>
        <id>repo.geyfman.net</id>
        <releases>
            <enabled>true</enabled>
            <checksumPolicy>ignore</checksumPolicy>
        </releases>
        <snapshots>
            <enabled>false</enabled>
        </snapshots>
        <url>https://github.com/anatolyg/mvn.geyfman.net/raw/master/releases</url>
    </repository>