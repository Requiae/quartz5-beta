---
title: Feats
tags:
  - list
---

```base
formulas:
  Untitled: file.links.filter(value.toString().contains("Species/"))
properties:
  note.prerequisite:
    displayName: Prerequisite
  formula.Untitled:
    displayName: Prerequisite
  file.name:
    displayName: Feat
  note.source:
    displayName: Source
views:
  - type: table
    name: Table
    filters:
      and:
        - file.tags.contains("feat")
    order:
      - file.name
      - source
      - formula.Untitled
    sort:
      - property: formula.Untitled
        direction: DESC
      - property: prerequisite
        direction: ASC
      - property: formula.Prerequisite
        direction: DESC
    columnSize:
      file.name: 294
      note.source: 187
      formula.Untitled: 217

```
