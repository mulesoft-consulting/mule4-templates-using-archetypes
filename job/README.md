# Archetype for Template: job

Used to generate the archetype for generating a skeleton job.

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

To generate an job skeleton using this archetype, use the command:

```
mvn archetype:generate -DarchetypeGroupId=org.mule.templates -DarchetypeArtifactId=job -DarchetypeVersion=1.0.0 -DartifactId=mytest-job -B
```
