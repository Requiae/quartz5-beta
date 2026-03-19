---
title: Species
tags:
  - list
---

```base
formulas:
  Inheritances: file.embeds.filter(value.asFile().hasTag("lineage")).map(value.asFile())
  Names: file.asLink(file.properties.title)
properties:
  formula.Names:
    displayName: Species
  formula.Inheritances:
    displayName: Lineages
  note.source:
    displayName: Source
views:
  - type: table
    name: Table
    filters:
      and:
        - file.tags.contains("species")
        - file.folder.contains("Species")
    groupBy:
      property: source
      direction: ASC
    order:
      - formula.Names
      - formula.Inheritances
    sort:
      - property: formula.Names
        direction: ASC
      - property: formula.Test
        direction: ASC
    columnSize:
      formula.Names: 150
      formula.Inheritances: 546

```
