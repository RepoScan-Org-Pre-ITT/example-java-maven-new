# [:] Example Maven Project

An example maven project to demonstrate [srcclr](https://www.srcclr.com) scans.sssf

## Try me!

```
brew tap srcclr/srcclrxx
brew install srcclr
srcclr activate
srcclr scan --url https://github.com/srcclr/example-java-maven
```

## With SourceClear's Maven Plugin
```
git clone https://github.com/srcclr/example-java-maven
cd example-java-maven
mvn clean compile com.srcclr:srcclr-maven-plugin:scan -DapiToken=<yourSourceClearToken>
```


Updated by Cypress on 2025-11-17T11:07:22.827Z

Updated by Cypress on 2025-11-17T11:20:52.757Z
