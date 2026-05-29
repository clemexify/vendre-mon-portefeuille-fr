# Vendre-mon-portefeuille.fr

Outil d'estimation et de mise en relation pour la cession de portefeuilles de courtage en assurance.

**→ [Accéder à la démo](https://clemexify.github.io/vendre-mon-portefeuille-fr/)**

---

## Ce que fait le projet

Un courtier en assurance qui souhaite céder son portefeuille peut :

1. **Obtenir une estimation rapide** de la valeur de son portefeuille en renseignant ses données clés (commissions récurrentes, mix de branches, taux de résiliation, qualité du carnet…)
2. **Générer une fiche de présentation** à destination d'un repreneur potentiel et de son banquier *(à venir)*
3. **Être mis en relation** avec des acheteurs sérieux dans sa région *(à venir)*

La méthode de valorisation s'appuie sur les pratiques de marché constatées en France pour la cession de portefeuilles de courtage (méthode du multiple de commissions récurrentes, ajusté par critères qualitatifs).

---

## Données

Le dossier `data/courtiers/` contient un export des entreprises enregistrées sous le code NAF **66.22Z** (agents et courtiers d'assurance), issu de la base SIRENE via l'API publique INSEE — mise à jour mensuelle.

---

## Contribuer

Le projet est en construction. Toute contribution est bienvenue.

### Tester la page

Ouvre [la démo](https://clemexify.github.io/vendre-mon-portefeuille-fr/) et remonte ce qui ne va pas : un calcul qui semble faux, un libellé qui manque de clarté, un bug d'affichage. Le plus simple : [ouvrir une issue](https://github.com/clemexify/vendre-mon-portefeuille-fr/issues/new).

### Contribuer au code

```bash
# 1. Forker le repo sur GitHub, puis cloner ton fork
git clone https://github.com/<ton-pseudo>/vendre-mon-portefeuille-fr.git
cd vendre-mon-portefeuille-fr

# 2. Créer une branche pour ta modification
git checkout -b ma-modification

# 3. Ouvrir index.html dans ton navigateur — pas de build, pas de dépendances
open index.html

# 4. Faire tes modifications, committer
git add .
git commit -m "Description de la modification"

# 5. Pousser et ouvrir une Pull Request
git push origin ma-modification
```

Pas de framework, pas de dépendances — juste un fichier HTML avec du CSS et du JS intégrés. N'importe quel éditeur de texte suffit.

### Pistes d'amélioration en cours

- [ ] Génération d'un PDF de présentation du portefeuille
- [ ] Affinage des coefficients par sous-branche
- [ ] Formulaire de contact / mise en relation
- [ ] Version mobile à peaufiner

---

## Licence

Usage libre pour tout professionnel de l'assurance. Code source sous licence MIT.
