# plantuml-service-icon

Service icons for PlantUML

## Usage

1. include common.puml

```
!define ServiceIconPuml https://raw.githubusercontent.com/sitateru/plantuml-service-icon/master
!include ServiceIconPuml/common.puml
```

2. include icon puml, and use

```
!include ServiceIconPuml/path/to/SomeIcon.puml

SomeIcon(alias, "label")
```
