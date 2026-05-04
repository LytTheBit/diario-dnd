---
{"dg-publish":true,"permalink":"/Curse of Strahd/Curse of Strahd/","tags":["Campagna","DnD"],"noteIcon":"","dg-note-properties":{"Sistema":"D&D","Master":"Lorenzo Grassi","Player":["Martina Schirona","Gabriele Attucci","Lorenzo Camuso","Nodar Varazashvili","Francesco Bonaiuti"],"tags":["Campagna","DnD"]}}
---

![Pasted image 20250331194452.png](/img/user/0-Immagini%20e%20altro/Lorenzo/Pasted%20image%2020250331194452.png)
Campagna creata da Lorenzo Grassi seguendo il manuale di Curse of strahd.

# Plot
Gli eroi devono sconfiggere [[Curse of Strahd/Personaggi/NPC/Nemici/Strahd\|Strahd]] per poter fuggire dal [[Curse of Strahd/Mondo/Regioni/Reame di Barovia\|Reame di Barovia]]

#### Missioni in corso
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

#### Missioni completate
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

# Sessioni
```base
filters:
  and:
    - file.inFolder("Curse of Strahd/Sessioni")
views:
  - type: cards
    name: "Sessioni - Strahd"
    image: immagine
    imageFit: cover
    order:
      - file.name
```

```base
filters:
  and:
    - file.inFolder("Curse of Strahd/Sessioni")
views:
  - type: cards
    name: "Sessioni - Strahd"
    image: immagine
    imageFit: cover
    order:
      - file.name
    sort:
      - property: file.name
        direction: ASC
```



# Player
```base
filters:
  and:
    - file.inFolder("Curse of Strahd/Personaggi/Party")
views:
  - type: cards
    name: "Party - Strahd"
    image: immagine
    imageFit: cover
    order:
      - file.name
```

