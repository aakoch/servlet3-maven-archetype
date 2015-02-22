#servlet3-maven-archetype

Project provides Maven archetype for creating plain simple Servlet 3 based web application

## Installation

### Clone this repository

```
$ git clone https://github.com/maciejwalkowiak/servlet3-maven-archetype.git
```

### Install it to local Maven repository

```
$ cd servlet3-maven-archetype
$ mvn install
```

### Create project based on this archetype

```
$ mvn archetype:generate \
    -DarchetypeGroupId=pl.maciejwalkowiak \
    -DarchetypeArtifactId=servlet3-webapp-archetype \
    -DarchetypeVersion=1.0.2
```

### Run project

```
$ mvn tomcat7:run
```
