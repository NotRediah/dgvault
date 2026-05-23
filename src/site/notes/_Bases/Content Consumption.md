---
{"publish":true,"dg-publish":true,"permalink":"/bases/content-consumption/","dgPassFrontmatter":true,"created":"2026-05-17T22:34:27.725+05:00","updated":"2026-05-24T00:22:02.248+05:00","dg-note-properties":{"publish":true}}
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


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - type.contains("lecture")
    order:
      - file.name
      - status
      - file.ctime
      - tags
      - topics covered
    sort:
      - property: file.ctime
        direction: DESC

```


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("clippings")
    order:
      - file.name
  - type: cards
    name: View

```
