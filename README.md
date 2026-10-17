# Logitech G - LIGHTSYNC

Intégration d'une page produit Logitech G à partir d'une maquette Figma.

## Maquette

Maquette réalisée sur Figma, construite avec des variables (couleurs, espacements, typographies) réutilisées dans le code :

https://www.figma.com/design/TkcgPfkjX8HERof0UQisf7/Logitech?node-id=0-1&t=kCXl88kt18KNOe4v-1

## Technologies

- HTML5 sémantique
- SCSS (modules `@use`, variables, maps, `@each`)
- CSS custom properties
- Figma

## Architecture CSS

- **SMACSS** : fichiers séparés par catégorie (base, layout, module, state).
- **BEM** : nommage des classes en `bloc__élément--modificateur` (ex. `card__switch--blue`).
- **OOCSS** : séparation structure / apparence, composants réutilisables (ex. `btn`, `btn--primary`).
