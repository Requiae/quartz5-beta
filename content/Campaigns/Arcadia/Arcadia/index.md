---
title: Arcadia
draft: false
---

```base
views:
  - type: leaflet-map
    name: Map
    filters:
      and:
        - file.path.contains("Arcadia/Arcadia/")
        - "!marker.isEmpty()"
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
