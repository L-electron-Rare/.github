# L'Electron Rare / FineFab

> *"The boundary between physical and non-physical is very imprecise for us."* — Donna Haraway

**Hardware embarqué et IA souveraine — local-first, multi-machine, sans dépendance au cloud.**

L'Electron Rare conçoit des systèmes électroniques sur mesure — design, conseil, formation — et développe **FineFab**, sa plateforme de fabrication : du firmware ESP32/STM32 à l'EDA assistée par IA.

Cette organisation héberge la **chaîne d'outils matériel & EDA souveraine** : moteur de pipeline EDA, co-design matériel multi-agent, ponts KiCad headless et toolkit de fine-tuning MLX. Le reste de l'écosystème vit ailleurs :

- 🧠 **IA souveraine → [ailiance](https://github.com/ailiance)** — la passerelle LLM EU-souveraine, l'agent de code **ISAAC** et le benchmark EU AI Act ont été détachés vers leur propre organisation (carve-out du 2026-05-11).
- 🏭 **Plateforme FineFab → [github.com/electron-rare](https://github.com/electron-rare)** — le monorepo *Factory 4 Life* et les services `life-*` / `makelife-*` sont rattachés au compte personnel pendant la phase de pré-lancement.
- 🔬 **Recherche cognitive → [Hypneum Lab](https://github.com/hypneum-lab)** — le framework **GENIAL**, open-science et pré-enregistré sur OSF.

---

## Dépôts de l'organisation

| Dépôt | Rôle |
|---|---|
| [`euclideda`](https://github.com/L-electron-Rare/euclideda) | Moteur d'orchestration de pipelines pour workflows EDA souverains (Rust). |
| [`hardware-coagent`](https://github.com/L-electron-Rare/hardware-coagent) | Co-design matériel multi-agent — contraintes paramétriques partagées entre méca, PCB, firmware et coût. |
| [`kicad-mcp-pro`](https://github.com/L-electron-Rare/kicad-mcp-pro) | Serveur MCP pilotant KiCad en mode headless (adapter NativeBoard) — alimente les validateurs du benchmark EU AI Act. |
| [`kiki-forge`](https://github.com/L-electron-Rare/kiki-forge) | Pipeline d'entraînement LLM multi-compute pour Mac Studio M3 Ultra. |
| [`mlx`](https://github.com/L-electron-Rare/mlx) | Fork du MLX d'Apple — patches de limites mémoire pour l'entraînement de grands modèles sur M3 Ultra. |
| [`qet-life`](https://github.com/L-electron-Rare/qet-life) | Fork de QElectroTech (schématique électrotechnique). |
| [`moodle`](https://github.com/L-electron-Rare/moodle) | Fork de Moodle — support du catalogue de formation. |

---

## Liens

[lelectronrare.fr](https://lelectronrare.fr) · [ailiance.fr](https://ailiance.fr) · [Hugging Face](https://huggingface.co/electron-rare) · [contact@lelectronrare.fr](mailto:contact@lelectronrare.fr)

---

*"Monsters have always defined the limits of community in Western imaginations."* — Donna Haraway
