# Framework DS – Playground de composants

Site de référence pour explorer les 54 composants de [shadcn/ui](https://ui.shadcn.com) (style `new-york`, Tailwind v4) et tester leurs propriétés en direct. Il sert de base de travail pour construire et documenter le Framework DS.

**Site en ligne :** https://mmamert.github.io/Framework_DS_storybook/

## Ce que l'on peut faire

- Parcourir les composants par catégorie ou via la recherche
- Modifier leurs propriétés (variantes, tailles, états) et voir le rendu en direct
- Copier le code correspondant
- Basculer entre le thème clair et le thème sombre
- Parcourir la documentation de chaque composants

## Lancer le projet en local

```
npm install
npm run dev
```

## Organisation du code

- `src/components/ui/` : composants basé sur shadcn/ui
- `src/playground/registry.tsx` : définition de chaque composant (propriétés configurables, rendu, extrait de code)
- `src/playground/Playground.tsx` : panneau de contrôles, prévisualisation et code
- `src/App.tsx` : navigation latérale, recherche, thème clair/sombre

Pour ajouter un composant ou enrichir ses propriétés testables, ajoutez une entrée dans `demos` (`registry.tsx`).

## Origine

Ce dépôt est une copie indépendante d'un playground shadcn/ui initié par Quentin <3.
