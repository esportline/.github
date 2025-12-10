# Contributing — Code (eSport Line)

## 📚 Table of Contents / Sommaire

- [English version](#english-version)
    - [How to contribute](#how-to-contribute)
    - [Commit message convention](#commit-message-convention)
    - [Reporting bugs & feature proposals](#reporting-bugs--feature-proposals)
    - [Review & merging process](#review--merging-process)
    - [License of contributions](#license-of-contributions)

- [Version Française](#version-française)
    - [Comment contribuer](#comment-contribuer)
    - [Convention de commit](#convention-de-commit)
    - [Signaler bugs & propositions](#signaler-des-bugs--faire-des-propositions)
    - [Processus de revue & intégration](#processus-de-revue--intégration)
    - [Licence des contributions](#licence-des-contributions)

---

## English version

### How to contribute

1. Fork the repository.
2. Clone your fork locally.
3. Create a **new branch** for your work (do not commit directly to `main` / `master`).  
   Example naming: `feature/your‑feature`, `fix/bug‑name`, `refactor/...`.
4. Make your changes or additions. If you add code that requires tests — **include or update tests accordingly**.
5. Ensure everything works (tests, build, linting, etc.).
6. Commit your changes following the commit message convention (see below).
7. Push your branch to your fork.
8. Open a **Pull Request (PR)** against the main repository.

### Commit message convention

We follow the **Conventional Commits** specification for commit messages.  
Commit messages must follow the format:

```
<type>[optional(scope)]: <short description>

[optional — more detailed description]

[optional — footer(s), e.g. BREAKING CHANGE, issue references, metadata]
```
Common commit types:

- `feat:` — new feature
- `fix:` — bug fix
- `docs:` — documentation only changes (README, docs, comments)
- `style:` — code style / formatting changes (whitespace, indentation, etc.) without logic changes
- `refactor:` — code changes that neither fix a bug nor add a feature
- `perf:` — performance improvements / optimizations
- `test:` — adding or modifying tests
- `chore:` — build process changes, maintenance tasks, tooling, dependencies, etc.

If your change introduces a **breaking change** (API change, backward-incompatible modification, etc.), indicate it using:

```
BREAKING CHANGE: <description of the breaking change>
```
in the commit body/footer.

### Reporting bugs & feature proposals

- If you find a bug — open an **issue** describing the problem: context, steps to reproduce, expected vs actual behavior.
- If you have a new idea or feature — open an issue first to discuss it before coding, so we can align on the scope and approach.
- Once discussed and accepted — create a branch and submit a PR.

### Review & merging process

- Every PR will be reviewed by maintainers (even internal contributions).
- Reviews are meant to be constructive and helpful — if changes are needed, maintainers will explain what must be modified.
- Aim for clear, well‑documented, maintainable code.

### License of contributions

By submitting code, you agree that your contribution will be licensed under the same license as the project (see `LICENSE` file in the root).

---

## Version Française

### Comment contribuer

1. Forkez le dépôt.
2. Clonez votre fork en local.
3. Créez une **nouvelle branche** pour votre travail (ne travaillez pas directement sur `main` / `master`).  
   Exemple de nommage : `feature/ma‑feature`, `fix/mon‑bug`, `refactor/...`.
4. Faites vos modifications / ajouts. Si vous ajoutez du code nécessitant des tests — **pensez à les ajouter ou mettre à jour**.
5. Vérifiez que tout fonctionne (tests, build, lint, etc.).
6. Commitez vos changements en suivant la convention de commit (voir ci‑dessous).
7. Poussez votre branche sur votre fork.
8. Ouvrez une **Pull Request (PR)** vers le dépôt principal.

### Convention de commit

Nous utilisons la spécification Conventional Commits pour les messages de commit.  
Le message de commit doit respecter le format :

```
<type>[optionnel(scope)]: <description concise>

[optionnel — description plus détaillée]

[optionnel — pied de commit : métadonnées, références, BREAKING CHANGE, etc.]
```
Types de commit recommandés :

- `feat:` — nouvelle fonctionnalité
- `fix:` — correction de bug
- `docs:` — modifications de documentation uniquement
- `style:` — changements de style / formatage sans impact logique
- `refactor:` — refactorisation de code sans ajout de fonctionnalité ou correction
- `perf:` — améliorations de performances / optimisations
- `test:` — ajout ou modification de tests
- `chore:` — maintenance, configuration, dépendances, etc.

Si votre modification introduit une **rupture de compatibilité** (changement d’API, modification non rétro‑compatible, etc.), précisez :

```
BREAKING CHANGE: <description de la rupture>
```

dans le corps ou le pied du commit.

### Signaler des bugs & faire des propositions

- Si vous trouvez un bug — créez une **issue** décrivant le problème : contexte, étapes pour reproduire, comportement attendu vs réel.
- Si vous avez une nouvelle idée ou fonctionnalité — créez d’abord une issue pour en discuter avant de coder, afin qu’on s’accorde sur la portée et la méthode.
- Une fois validée — créez une branche et soumettez une PR.

### Processus de revue & intégration

- Toute PR sera revue par les mainteneurs (même les contributions internes).
- Les revues sont constructives — si des changements sont nécessaires, les mainteneurs expliqueront ce qu’il faut améliorer.
- L’objectif : du code clair, bien documenté, facile à maintenir.

### Licence des contributions

En soumettant du code, vous acceptez que votre contribution soit intégrée sous la même licence que le projet (voir le fichier `LICENSE` à la racine).

