# L'Electron Rare

> *"The boundary between physical and non-physical is very imprecise for us."* — Donna Haraway

**Systèmes électroniques spécifiques et IA locale — sans dépendance au cloud.**

L'Electron Rare conçoit, met au point et fiabilise des systèmes électroniques sur mesure — automatismes, ensembles liés à l'énergie, contrôleurs de scène — et forme au PCB, à KiCad et aux microcontrôleurs. La R&D porte sur l'IA qui tourne en local : modèles ouverts fine-tunés par domaine, inférence sur Apple Silicon, assistants personnels *local-first*.

Cette organisation héberge la **chaîne d'outils matériel & EDA** de l'entreprise : moteur de pipeline EDA, co-design matériel multi-agent, pont KiCad headless et toolkit de fine-tuning MLX. Le reste de l'écosystème vit ailleurs :

- ⚡ **Projets publics et personnels → [github.com/electron-rare](https://github.com/electron-rare)** — escape room Zacus, AV-Live, contrôleurs DMX/ESP32, mascarade, méthodologie Kill_LIFE.
- 🔬 **Recherche cognitive → [Hypneum Lab](https://github.com/hypneum-lab)** — le framework **GENIAL**, open-science et pré-enregistré sur OSF.
- 📦 **IA souveraine → [ailiance](https://github.com/ailiance)** *(clos)* — passerelle LLM EU-souveraine, agent de code ISAAC et benchmark EU AI Act, détachés en mai 2026 ; développement arrêté en octobre 2026, dépôts publics conservés.

---

## Dépôts de l'organisation

| Dépôt | Rôle |
|---|---|
| [`euclideda`](https://github.com/L-electron-Rare/euclideda) | Moteur d'orchestration de pipelines pour workflows EDA souverains (Rust). Phase 0. |
| [`hardware-coagent`](https://github.com/L-electron-Rare/hardware-coagent) | Co-design matériel multi-agent — contraintes paramétriques partagées entre méca, PCB, firmware et coût. |
| [`kicad-mcp-pro`](https://github.com/L-electron-Rare/kicad-mcp-pro) | Serveur MCP pilotant KiCad en mode headless (adapter NativeBoard). |
| [`kiki-forge`](https://github.com/L-electron-Rare/kiki-forge) | Pipeline d'entraînement LLM multi-compute pour Mac Studio M3 Ultra. |
| [`mlx`](https://github.com/L-electron-Rare/mlx) | Fork du MLX d'Apple — patches de limites mémoire pour l'entraînement de grands modèles sur M3 Ultra. |
| [`qet-life`](https://github.com/L-electron-Rare/qet-life) | Fork de QElectroTech (schématique électrotechnique). |
| [`moodle`](https://github.com/L-electron-Rare/moodle) | Fork de Moodle — a servi au catalogue de formation 2026 (plateforme fermée). |

Les dépôts privés sont des prototypes internes (dont **FineFab / Factory 4 Life**, plateforme de fabrication du firmware à l'EDA assistée par IA).

---

## Liens

[lelectronrare.fr](https://www.lelectronrare.fr) · [Hugging Face](https://huggingface.co/electron-rare) · [contact@lelectronrare.fr](mailto:contact@lelectronrare.fr)

---

*"Monsters have always defined the limits of community in Western imaginations."* — Donna Haraway

*Mis à jour le 2026-10-25.*
