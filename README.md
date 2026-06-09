## rote_ressourcen_26l2

### ⚠️ BIS PROJEKTSTART GEHEIM ⚠️

Ressourecenpaket für LDARS-2, 2026

[<img width="400px" alt="Download Badge" src="https://shieldcn.dev/badge/rote_ressourcen_26l2.zip-Download-22c55e.svg?mode=light&logo=ri%3ATbDownload">](https://github.com/TobSnom269/superdupergeheim/releases/download/latest/rote_ressourcen_26l2.zip)
</br><sub>(https://github.com/TobSnom269/superdupergeheim/releases/download/latest/rote_ressourcen_26l2.zip)</sub>

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
- Für Custom Item Namen: Immer translation für Englisch und Deutsch anfertigen und als Fallback "! Missing Resource Pack !" angeben.
    
##### Im Git
- commits auf Deutsch
