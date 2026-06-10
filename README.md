## rote_ressourcen_26l2
Ressourecenpaket für LDARS-2, 2026 <img width="70px">  (⚠️ BIS PROJEKTSTART GEHEIM ⚠️)

[<img width="400px" alt="Download Badge" src="https://shieldcn.dev/badge/rote_ressourcen_26l2.zip-Download-22c55e.svg?mode=light&logo=ri%3ATbDownload">](https://github.com/TobSnom269/superdupergeheim/releases/download/latest/rote_ressourcen_26l2.zip)
</br><sub>(https://github.com/TobSnom269/superdupergeheim/releases/download/latest/rote_ressourcen_26l2.zip)</sub>


#### Konvention:

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
- Für die language files gillt:
    - Für Item Namen: `name.item.ldars.(...)`
    - Für Item Descriptions: `description.item.ldars.(...)`
    - (...): ab hier kann die eigentliche Item bezeichnung kommen. Solltet ihr mehrere Items hinzüfügen die einer gleichen Übergruppe zugeordnet werden können, macht das bitte mit neuen abschnitten (zb.: `name.item.ldars.*vegan*.vegan_egg`). "vegan" ist hier quasi wie ein neuer Unterordner.
    - Für alles weitere einfach dieser generellen Struktur folgen und einfach an dem orientieren, was schon vorhanden ist.
    
##### Im Git
- commits auf Deutsch oder Englisch ist eigentlich egal
