---
{"dg-publish":true,"permalink":"/Home/","tags":["gardenEntry"],"noteIcon":"","dg-note-properties":{}}
---

Benvenuto nel [[Francesco Bonaiuti\|mio]] diario delle campagne di D&D!



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/Curse of Strahd/Curse of Strahd/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




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



</div></div>




<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/Reami Silvestri/Per i Reami Silvestri/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Campagna creata da Nodar... attualmente senza un nome

# Sessioni
- [[Reami Silvestri/Sessioni/(1) Arco di Visperwood/Nodar sessione 1\|Nodar sessione 1]]
- [[Reami Silvestri/Sessioni/(1) Arco di Visperwood/Nodar sessione 2\|Nodar sessione 2]]
- [[Reami Silvestri/Sessioni/(1) Arco di Visperwood/Nodar sessione 3\|Nodar sessione 3]]
- [[Reami Silvestri/Sessioni/(2) Arco di Boscoscuro/Nodar sessione 4\|Nodar sessione 4]]
- [[Reami Silvestri/Sessioni/(2) Arco di Boscoscuro/Nodar sessione 5\|Nodar sessione 5]]
- [[Reami Silvestri/Sessioni/(2) Arco di Boscoscuro/Nodar sessione 6\|Nodar sessione 6]] 
- [[Reami Silvestri/Sessioni/(2) Arco di Boscoscuro/Nodar sessione 7\|Nodar sessione 7]]  
- [[Reami Silvestri/Sessioni/(2) Arco di Boscoscuro/Nodar sessione 8\|Nodar sessione 8]]
- [[Nodar sessione 9\|Nodar sessione 9]]
# Player
- [[Reami Silvestri/Personaggi/Party/Singrid\|Singrid]] di Luisa Seres
- [[Reami Silvestri/Personaggi/Party/Ashtar\|Ashtar]] di Martina Schirone
- [[Reami Silvestri/Personaggi/Party/Minimoto\|Minimoto]] di Francesco Bonaiuti



</div></div>

