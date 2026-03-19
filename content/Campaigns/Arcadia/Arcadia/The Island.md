---
title: The Island of Arcadia
draft: false
prioritise: true
---

Similar notes:

- [[Ancient Arcadia|The ancient civilisation of Arcadia]]
- [[Arcadia City|The city of Arcadia]]
- [[Arcadia Central|Arcadia Central Station]]

## Map

```base
views:
  - type: leaflet-map
    name: Map
    filters:
      and:
        - file.path.contains("Arcadia/Arcadia/")
        - '!marker.filter(value.mapName == "Arcadia").isEmpty()'
    mapName: Arcadia
    image: arcadia.webp
    height: 400
    minZoom: -2
    maxZoom: 0
    defaultZoom: -1.5
    zoomDelta: 0.25
    scale: "0.2"
    unit: km

```

## The underground train network

```base
views:
  - type: leaflet-map
    name: Map
    filters:
      and:
        - file.path.contains("Arcadia/Arcadia/")
        - '!marker.filter(value.mapName == "Arcadia Underground").isEmpty()'
    mapName: Arcadia Underground
    image: arcadia_underground.webp
    height: 400
    minZoom: -2.1
    maxZoom: -1.1
    defaultZoom: -2.1
    zoomDelta: 0.25
    scale: "0.2"
    unit: km

```
