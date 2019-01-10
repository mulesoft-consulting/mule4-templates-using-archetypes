# archetype-process-api

Used to generate the archetype for generating a skeleton Process API.

## Install Archetype on Workstation
To install this project in the local workstation Maven repository, clone this repository and from the cloned directory:

```
mvn install
```
## Deploy Archetype to Artifact Repository

```
mvn deploy -Partifact-repo
```

## Generating a Skeleton Project

To generate an Process API skeleton using this archetype, use the command:

```
mvn archetype:generate -DarchetypeGroupId=org.mule.templates -DarchetypeArtifactId=prc-api -DarchetypeVersion=1.0.0 -DartifactId=mytest-exp-api -B
```
