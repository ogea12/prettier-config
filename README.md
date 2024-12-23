# @ogea12/prettier-config

<div align="center">

![Version](https://img.shields.io/npm/v/@ogea12/prettier-config?style=for-the-badge&colorA=4c566a&colorB=5382a1&logo=npm&logoColor=white)
![Code Size](https://img.shields.io/github/languages/code-size/ogea12/prettier-config?style=for-the-badge&colorA=4c566a&colorB=ebcb8b&logo=github&logoColor=white)
![License](https://img.shields.io/github/license/ogea12/prettier-config?style=for-the-badge&colorA=4c566a&colorB=a3be8c)

</div>

`@ogea12/prettier-config` est un package permettant de bénéficier de la configuration [Prettier](https://prettier.io) utilisée dans les projets de l'OGEA 12.

## Premiers pas

### Installation

Pour utiliser le package, vous devez d'abord l'intégrer dans votre projet.

```bash
npm install -D @ogea12/prettier-config

# Assurez-vous également d'installer le package suivant
npm install -D prettier
```

### Utilisation

Une fois l'installation terminée, vous pouvez ajouter le bloc de code suivant dans le fichier `package.json` pour bénéficier de la configuration Prettier.

```jsonc
// package.json

{
  "prettier": "@ogea12/prettier-config",
}
```

Vous pouvez également ajouter un script pour utiliser le formateur Prettier dans le fichier `package.json`. Après avoir ajouté le script, vous pouvez exécuter la commande `npm run format` afin de formater les fichiers du projet, à l'exception des fichiers présents dans un potentiel `.prettierignore`.

```jsonc
// package.json

{
  "scripts": {
    "format": "prettier --write .",
  },
}
```
