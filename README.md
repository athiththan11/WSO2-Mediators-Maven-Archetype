# WSO2 Mediators Maven Archetype <!-- omit on toc -->

Maven Archetype for WSO2 Class Mediators. Use the following maven archetype to generate maven projects to implement WSO2 related class mediators for WSO2 API Manager and WSO2 EI Services.

```xml
<dependency>
    <groupId>com.athiththan.wso2</groupId>
    <artifactId>wso2-mediators</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Usage

```shell
mvn archetype:generate  -DarchetypeGroupId=com.athiththan.wso2      \
                        -DarchetypeArtifactId=wso2-mediators        \
                        -DarchetypeVersion=1.0.0                    \
                        -DgroupId=<Group ID>                        \
                        -DartifactId=<Artifact ID>
```
