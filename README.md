# MIMIC: Music Intelligence and Machine Inspired Composition

### Music Generation with Deep Learning

### Abstract
MIMIC est un projet de recherche visant à explorer la génération musicale par intelligence artificielle, avec un accent particulier sur le jazz manouche et le compositeur Stéphane Grappelli. L'objectif est d'entraîner un modèle capable de produire des compositions originales fidèles à ce style. Ce projet s'inscrit dans une initiative plus large visant à faire perdurer la musique d'artistes défunts avec des performances artistiques originales.

### Introduction
Le projet MIMIC repose sur des modèles de deep learning, en particulier des architectures basées sur Transformers, pour la génération musicale.

### Approche
Nous avons adopté une approche progressive en deux étapes :
* [x] ✅ **Génération mélodique** : Entraînement d'un modèle à produire des mélodies jazz cohérentes.
* [ ] ❌ **Fine-tuning** : Spécialisation du modèle pour capturer les nuances stylistiques.

Nous avons exploré plusieurs techniques d'encodage musical, et optimisé notre pipeline d'apprentissage en utilisant des blocs d'attention.

### Résultats et limites
Bien que notre modèle ait montré des capacités prometteuses, les contraintes matérielles (GPU 8GB de VRAM) ont limité nos performances. La génération musicale manque encore de cohérence à long terme et la fidélité au style visé reste perfectible. Une augmentation des ressources de calcul ou l'exploration d'architectures moins gourmandes en ressources serait nécessaire pour améliorer les résultats.

### Perspectives
- **Optimisation du modèle** : Expérimenter des architectures plus légères et efficaces.
- **Amélioration de la tokenisation** : Affiner l'encodage MIDI pour une meilleure capture des structures harmoniques.
- **Augmentation des données d'entraîment** : Intégrer un jeu de données plus large et mieux annoté.
- **Application à la génération vocale** : Intégrer un module IA pour la superposition de voix chantées.

### Installation et utilisation
- Clonez ce repository :
   ```bash
   git clone https://github.com/votre-repo/Music-generation.git
   cd Music-generation
   ```
### 📄 [Rapport](https://github.com/maxarasta/Music-generation/blob/main/PDF/rapport-music-generation-with-ai-beaudoin-margouty.pdf)

### 📄 [Présentation](https://github.com/maxarasta/Music-generation/blob/main/PDF/presentation-music-generation-with-ai-beaudoin-margouty.pdf)

### Auteurs
- [@Ttheau748K](https://github.com/Ttheau748K)
- [@maxarasta](https://github.com/maxarasta)

### Conclusion
MIMIC constitue une première étape vers la génération de musique jazz de haute qualité par IA. Si nos résultats actuels montrent une marge de progression, notre approche a démontré son potentiel et ouvre la voie à des applications futures dans la création musicale automatisée et la résurgence d'artistes emblématiques via la technologie.
