# mule4-templates-using-archetypes
Using Maven archetype to create starting Mule4 projects from a template

## Install All Archetype templates on Workstation
To install this project in the local workstation Maven repository, clone this repository and from the cloned directory:

```
mvn install
```
## Deploy All Archetype to Artifact Repository

```
mvn deploy -Partifact-repo
```

Note that these are the other GitHub projects that will be required for these templates to work:

* https://github.com/mulesoft-consulting/mule4-cps-encryption -release 1.1.2
* https://github.com/mulesoft-consulting/mule4-totp -release 1.0.2
* https://github.com/mulesoft-consulting/mule4-eframework-connector -release 1.1.0
* https://github.com/mulesoft-consulting/minimal-logging -release 1.0.1
* https://github.com/mulesoft-consulting/mule4-cps-rest-service -release 1.0.2
* https://github.com/mulesoft-consulting/mule4-cps-connector -release 1.0.4
* https://github.com/mulesoft-consulting/CpsTool -release 1.3.2



