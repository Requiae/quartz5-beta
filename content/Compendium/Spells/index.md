---
title: Spells
tags:
  - list
---
```base
properties:
  file.name:
    displayName: Spell
  note.level:
    displayName: Level
  note.school:
    displayName: School
  note.source:
    displayName: Source
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder.contains("Spells")
        - file.tags.contains("spell")
    order:
      - file.name
      - level
      - school
      - source
    sort:
      - property: level
        direction: ASC
    columnSize:
      file.name: 287
      note.level: 96
      note.school: 124
      note.source: 174

```