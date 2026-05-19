---
{"dg-publish":true,"permalink":"/100-inbox/content-consumption/","created":"2026-05-17T22:55:24.116+05:00","updated":"2026-05-17T22:55:24.116+05:00","dg-note-properties":{"publish":true}}
---


```base
views:
  - type: cards
    name: Table
    filters:
      and:
        - type.contains("video")
    order:
      - file.name
      - status
      - published
      - watched
      - processed
    image: note.image
    imageFit: contain

```

