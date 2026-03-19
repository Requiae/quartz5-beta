---
title: Dryad
source: Homebrew
tags:
  - homebrew
  - species
---

> [!quote|clean] Sorisana Herbalar, master botanist
> Dryads are beautiful creatures, bountiful resources, and irritable souls. Best keep them friendly lest you end up like some of my previous students, as fertiliser.

Dryads are magical, fey creatures who embody the spirit of a tree. Once a tree has grown in a sacred grove for a century or more, a dryad may emerge, fully formed, to serve as the grove’s protector and friend. Occasionally, such beings wander from their groves, perhaps because another dryad has emerged to protect the grove.

Dryads have the form of a young human or elf, but their hair looks like green, red, or golden leaves and their smooth skin resembles green, golden, or brown bark.

## Dryad Traits

**Ability Score Increase.** Your Charisma score increases by 1 and your Wisdom by 1.

**Age.** Dryads grow slowly, taking nearly 60 years to reach maturity. Once they have, however, they can live up to 250 years.

**Size.** Dryads are roughly human in size and weight. Your size is Medium.

**Speed.** Your base walking speed is 30 feet.

**Hybrid nature.** You have two creature types: humanoid and fey. You can be affected by a game effect if it works on either of your creature types. As a fey, you have advantage on saving throws against being charmed, and magic can't put you to sleep.

**Photosynthesis.** If you spend an hour in direct sunlight or an hour with your feet in fertile soil, you do not need to eat or drink for the next 24 hours.

**Speech of Beast and Leaf.** You have the ability to communicate in a limited manner with beasts and plants. They can understand the meaning of your words, and can respond by communicating simple ideas.

**Languages.** You can speak, read, and write Common and Sylvan.

## Lineages

There are as many kinds of dryads as are there are species of tree. Below are some of the most common ones.

### Apple dryad

![[Apple | no-title no-link clean]]

### Cherry dryad

![[Cherry | no-title no-link clean]]

### Oak dryad

![[Oak | no-title no-link clean]]

### Pine dryad

![[Pine | no-title no-link clean]]

### Willow dryad

![[Willow | no-title no-link clean]]

## Racial Feats

```base
properties:
  file.name:
    displayName: Feat
views:
  - type: table
    name: table
    filters:
      and:
        - file.tags.containsAll("racial-feat", "feat")
        - prerequisite.contains("dryad")
    order:
      - file.name
    coverFallback: preview
    cardSize: 240
    imageAspectRatio: 1.3

```
