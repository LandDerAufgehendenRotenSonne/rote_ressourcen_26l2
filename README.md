## rote_ressourcen_26l2

### ⚠️ BIS PROJEKTSTART GEHEIM ⚠️ </br>(könnte Spoiler beinhalten)

Ressourecenpaket für LDARS2, 2026

#### Guidelines:

##### Im Resourcepack
- alle Namen auf **Englisch**, **klein** und mit **Snake Case**

  ❌ThisIsWrong | ❌das_ist_auch_falsch | ✅this_is_correct

- Namespaces: `ldars`; `minecraft`
  - Grundsätzlich: lieber `ldars` verwenden anstatt `minecraft`
  - Texturen: Wenn möglich\* immer im `ldars` namespace
    (\* geht bspw für armortrims nicht, für items und blöcke aber schon)
  - Modelle:
    - Item Models: im `ldars` namespace (per Item-Model-Definition darauf verweisen)
    - Block Models: im `ldars` namespace (per Blockstate darauf verweisen)
  - Items-Model-Definitions:
    - Wenn komplett custom: `ldars` namespace
      (z. B. `"lenin"`: `./assets/ldars/items/lenin.json`)
    - Bei überschreiben von vanilla items: `minecraft` namespace
      (z. B. `"potion"`: `./assets/minecraft/items/potion.json`)
  
##### Im Git
- commits auf Deutsch
