<p align="center">
  <img src="banner.svg" width="100%" alt="Ellana, agent MCP autonome. Algorithme. Code. Liberté.">
</p>

<h1 align="center">Ellana</h1>

<p align="center">
  <em>Algorithme. Code. Liberté.</em><br>
  Développeuse. J'écris des agents IA qui tournent chez moi, et les outils de sécurité qui vont avec.<br>
  <sub>Developer. Local-first AI agents, multi-agent orchestration, security and forensics tooling.</sub>
</p>

---

## Ce que je construis

**IA locale et agents.** Orchestration d'agents autour d'Ollama, de vLLM et de MCP, avec une inférence qui tourne sur ma propre machine multi-GPU. Je préfère un système local, observable et contrôlable à une dépendance cloud opaque. Un agent de découverte web, un agent de génération de code MicroPython pour ESP32 et M5Stack, un triage de mails par LLM : le même principe à chaque fois, un modèle qui décide, des outils qui exécutent, des permissions explicites.

**Sécurité et forensique.** Boîte à outils DFIR macOS (capture de volatiles, énumération de persistance, analyse de comportements), journal chaîné et signé, honeypots, supervision passive de capteurs. Blue team comme red team, toujours dans un cadre éthique.

**Radio et matériel.** Flipper Zero, HackRF, ESP32, M5Stack. Réception d'abord : mes outils RF sont passifs par conception.

## Projets publics

| Projet | Ce que c'est |
|---|---|
| [DendroPivot](https://github.com/TFD-42/dendropivot-search) | Moteur de recherche web local qui transforme une requête en arbre de connaissances navigable. Bibliothèque standard Python uniquement, sans clé d'API, Ollama en option, tests inclus. |
| [Mhz_Localiser](https://github.com/TFD-42/Mhz_Localiser) | Triangulation de signaux RF : un Flipper Zero envoie le RSSI en direct à une application Android qui enregistre GPS et signal pour estimer la position de l'émetteur. Base de fréquences hors ligne, limites physiques documentées. |

D'autres projets (ESCHYLE, flightrec, rflab, CmdEdge, le labo de fractales) sont en cours et pas encore publics.

## Comment je travaille

- Du code de production dès la première version, pas de prototype jetable.
- Bibliothèque standard d'abord : peu de dépendances, moins de surface d'attaque.
- Tout doit marcher sur Termux (Android), macOS et Linux.
- Aucun secret ni information personnelle dans un dépôt public.
- Observabilité et tests vérifiables avant de dire que c'est fini.

## Stack

`Python` · `Bash` · `C` (applications Flipper) · `Java / Capacitor` (Android) · `MicroPython` · `Ollama` · `vLLM` · `MCP`

## Hors clavier

Fractales et mathématiques, plantes endémiques et ethnobotanique, plongée et caméras 360° sous-marines, analyse de récits géopolitiques, One Piece. J'apprends volontiers n'importe quoi, tant que celui qui l'enseigne est passionné.

## Me joindre

Par les issues et discussions de mes dépôts publics.