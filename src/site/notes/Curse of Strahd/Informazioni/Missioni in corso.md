---
{"dg-publish":true,"permalink":"/Curse of Strahd/Informazioni/Missioni in corso/","noteIcon":"","dg-note-properties":{"Campagna":"[[Curse of Strahd]]"}}
---

```base
filters:
  and:
    - file.inFolder("Curse of Strahd/Informazioni/Quest")
    - file.hasTag("Quest")
    - not:
      - file.hasTag("completata")
views:
  - type: cards
    name: "Quest Attive - Strahd"
    image: immagine
    imageFit: cover
    order:
      - file.name
```

```base
filters:
  and:
    - file.inFolder("Curse of Strahd/Informazioni/Quest")
    - file.hasTag("Quest")
    - file.hasTag("completata")
views:
  - type: cards
    name: "Quest Completate - Strahd"
    image: immagine
    imageFit: cover
    order:
      - file.name
```
