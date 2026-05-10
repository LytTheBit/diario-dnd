---
{"dg-publish":true,"permalink":"/Curse of Strahd/Curse of Strahd/","contentClasses":"cards","tags":["Campagna","DnD"],"noteIcon":"","dg-note-properties":{"Sistema":"D&D","Master":"Lorenzo Grassi","Player":["Martina Schirona","Gabriele Attucci","Lorenzo Camuso","Nodar Varazashvili","Francesco Bonaiuti"],"tags":["Campagna","DnD"]}}
---


![Pasted image 20250331194452.png](/img/user/0-Immagini%20e%20altro/Lorenzo/Pasted%20image%2020250331194452.png)
Campagna creata da Lorenzo Grassi seguendo il manuale di Curse of strahd.

# Plot
Gli eroi devono sconfiggere [[Curse of Strahd/Personaggi/NPC/Nemici/Strahd\|Strahd]] per poter fuggire dal [[Curse of Strahd/Mondo/Regioni/Reame di Barovia\|Reame di Barovia]]

```base
filters:
  and:
    - file.inFolder("Curse of Strahd")
    - file.hasTag("Quest")
    - not:
      - file.hasTag("completata")
views:
  - type: cards
    name: "Quest Attive"
    image: immagine
    imageFit: cover
    order:
      - file.name
```

```base
filters:
  and:
    - file.inFolder("Curse of Strahd")
    - file.hasTag("Quest")
    - file.hasTag("completata")
views:
  - type: cards
    name: "Quest Completate"
    image: immagine
    imageFit: cover
    order:
      - file.name
```

# Character
|                                                                                                  | Personaggio                                                                              |
| ------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| ![0-Immagini e altro/Lorenzo/Gabriel Noctis.png\|Gabriel Noctis.png](/img/user/0-Immagini%20e%20altro/Lorenzo/Gabriel%20Noctis.png)                           | [[Curse of Strahd/Personaggi/Party/Gavriel Noctis\|Gavriel Noctis]]                   |
| ![0-Immagini e altro/Lorenzo/Kenjiro Nozomi.png\|Kenjiro Nozomi.png](/img/user/0-Immagini%20e%20altro/Lorenzo/Kenjiro%20Nozomi.png)                           | [[Curse of Strahd/Personaggi/Party/Kenjiro Nozomi\|Kenjiro Nozomi]]                   |
| ![0-Immagini e altro/Lorenzo/Mevis Noctis.png\|Mevis Noctis.png](/img/user/0-Immagini%20e%20altro/Lorenzo/Mevis%20Noctis.png)                               | [[Curse of Strahd/Personaggi/Party/Mavis Noctis\|Mavis Noctis]]                       |
| ![0-Immagini e altro/Lorenzo/Pasted image 20250406173035.png\|Pasted image 20250406173035.png](/img/user/0-Immagini%20e%20altro/Lorenzo/Pasted%20image%2020250406173035.png) | [[Curse of Strahd/Personaggi/Party/Sigfrit Von Drachenfels\|Sigfrit Von Drachenfels]] |
| ![0-Immagini e altro/Lorenzo/Thomas Bertrand.png\|Thomas Bertrand.png](/img/user/0-Immagini%20e%20altro/Lorenzo/Thomas%20Bertrand.png)                         | [[Curse of Strahd/Personaggi/Party/Thomas Bertrand\|Thomas Bertrand]]                 |
| ![0-Immagini e altro/Dice Home.png\|Dice Home.png](/img/user/0-Immagini%20e%20altro/Dice%20Home.png)                                             | [[Curse of Strahd/Personaggi/Party/Zi Han\|Zi Han]]                                   |

{ .block-language-dataview}

# Sessioni
```base
filters:
  and:
    - file.inFolder("Curse of Strahd/Sessioni")
views:
  - type: cards
    name: "Sessioni"
    image: immagine
    imageFit: cover
    order:
      - file.name
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

