---
title: The Alchemist's Guild
tags:
  - Alchemists-Guild
---

## Leadership

Something about a board of directors

## Membership

There are some requirements to join the Alchemist's Guild. An applicant either need to be apprenticed to an existing member of intermediate rank or above, or show your knowledge or skills in a recognised field of alchemy. Since the guild also functions as their member's guarantor they have little need to recruit members, instead they focus on properly ranking their members and enforcing their regulations. To be capable of this, the guild employs a strong administrative branch.
### Specialisations and Ranks

> [!caption| right wsmall no-border no-table-header]
> 
> |  |   
> | ------ | 
> | Novice     |
> | Initiate     |
> | Apprentice     |
> | Intermediate     |
> | Adept     |
> | Master     |
> | Grandmaster     |

The Alchemist's Guild separates its members into specialisations and ranks (see table). Most specialisations are focused on either research or production. The Guild's employees are also specialised, but their work tends to be of more administrative nature such as performing inspections, enforcing regulations, and generally keeping the guild running smoothly.

Members and employees can climb the ranks by showing both mastery of their specialisation and contributing to the Guild, be it by doing research, providing resources, or performing administrative duties.


### Note-worthy Members

```base
properties:
  file.name:
    displayName: Individual
  note.rank:
    displayName: Rank
  note.job:
    displayName: Specialisation
views:
  - type: table
    name: Table
    filters:
      and:
        - file.tags.contains("Alchemists-Guild")
        - "!rank.isEmpty()"
        - "!job.isEmpty()"
    order:
      - file.name
      - rank
      - job
    sort: []
    columnSize:
      file.name: 325
      note.rank: 123
      note.job: 250

```