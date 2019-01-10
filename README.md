# mule4-archetype-templates
Using Maven archetype to create starting Mule4 projects from a template

## Install All Archetype templates on Workstation
To install this project in the local workstation Maven repository, clone this repository and from the cloned directory:

```
mvn install
```
## Deploy Archetype to Artifact Repository

```
mvn deploy -Partifact-repo
```

Note that these are the other GitHub projects that will be required for these templates to work:

* https://github.com/mulesoft-consulting/mule4-cps-rest-service
* https://github.com/mulesoft-consulting/mule4-cps-connector
* https://github.com/mulesoft-consulting/CpsTool
* https://github.com/mulesoft-consulting/mule4-eframework-connector
* https://github.com/mulesoft-consulting/minimal-logging
* 