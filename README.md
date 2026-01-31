# Réalisation des circuits électroniques — UCD IA 2024/2025

Ce dépôt contient les ressources, schémas et fichiers de réalisation pour le cours "Réalisation des circuits électroniques" (UCD — Intelligence Artificielle) pour l'année universitaire 2024/2025.

## Objectif

Centraliser les travaux pratiques, schémas, routages et fichiers de fabrication (Gerber, BOM, etc.) produits pendant le semestre. Le dépôt sert de référence pour :
- les devoirs et TP,
- la documentation des circuits réalisés,
- les fichiers nécessaires à la fabrication et à la simulation.

## Contenu du dépôt (organisation suggérée)

- `docs/` — documents de cours, rapports et fiches techniques
- `schematics/` — fichiers de schémas (KiCad, Eagle, Fritzing, ...)
- `pcb/` — projets PCB (KiCad board, gerber, fabrication)
- `simulations/` — fichiers de simulation (LTspice, SPICE, Python notebooks)
- `firmware/` — code embarqué si applicable
- `assets/` — photos, images des prototypes
- `reports/` — rapports de TP et comptes-rendus

Adaptez la structure aux besoins : chaque TP peut avoir son propre sous-dossier (ex. `TP1/`, `TP2/`).

## Comment utiliser ce dépôt

1. Cloner le dépôt :

   ```bash
   git clone https://github.com/Dostofine/realisation_des_circuits_electronique_UCD_IA_2024_2025.git
   cd realisation_des_circuits_electronique_UCD_IA_2024_2025
   ```

2. Ouvrir les schémas/PCB :
   - KiCad : ouvrez les fichiers `.sch` et `.kicad_pcb` depuis l'interface KiCad.
   - LTspice : ouvrez les fichiers `.asc` dans LTspice pour lancer des simulations.

3. Générer les fichiers de fabrication :
   - Depuis KiCad, exporter les Gerber et le drill pour la fabrication.
   - Vérifier la BOM (`.csv`) et les valeurs de composants avant commande.

## Bonnes pratiques

- Ajouter un README spécifique dans chaque sous-dossier décrivant le contenu et la procédure pour reproduire le travail.
- Versionner les fichiers sources (schéma, PCB) — évitez de committer uniquement des exports binaires sans les sources.
- Documenter les choix de conception, schémas de test et résultats de simulation dans `reports/`.

## Contribution

1. Créez une branche feature/TPn-votreNom
2. Ajoutez vos fichiers et un rapport dans le dossier correspondant
3. Ouvrez une Pull Request décrivant les modifications

## Licence

Précisez ici la licence du dépôt (par exemple MIT, CC-BY, etc.). Si aucune licence n'est choisie, le dépôt est soumis aux droits d'auteur par défaut.

## Contact

Mainteneur : Dostofine

Pour toute question sur le cours ou le dépôt, ouvrez une issue ou contactez le mainteneur via son profil GitHub.
