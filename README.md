# Devenir une IT Woman

## Synopsis

*« Devenir une IT Woman »* est un guide pratique pour les femmes souhaitant embrasser une carrière dans les technologies de l'information. Ce livre propose des conseils, témoignages et ressources pour accompagner les lectrices à chaque étape de leur parcours IT. 

## Auteurs
- **Kevin Delfour** : Expert en IT, défenseur de la diversité et inclusion dans les technologies.
- **Houleymatou Baldé** : Ingénieure en informatique, co-fondatrice de Yeeso, engagée pour l'accès des femmes aux carrières IT.

---

## Installation

Ce projet utilise **mdBook** pour générer et servir le contenu en ligne. Si vous n'avez pas encore installé **mdBook**, suivez les étapes ci-dessous.

### Prérequis
#### Sur Linux
```bash
sudo snap install mdbook
```

### Lancer le livre en local

Pour lancer le livre en local et le visualiser dans votre navigateur :

1. Clonez ce repository :
```bash
git clone git@github.com:yeeso-lyon/Ebook_Devenir_IT_Woman.git
cd Ebook_Devenir_IT_Woman
```

2. Servez le livre en local avec la commande suivante :
```bash
mdbook serve --open
```

Cela démarrera un serveur local et ouvrira automatiquement votre navigateur par défaut pour visualiser le livre. Les modifications apportées aux fichiers seront automatiquement rechargées dans le navigateur.

### Ajouter un nouveau chapitre

Les chapitres du livre sont listés dans le fichier `src/SUMMARY.md`. Pour ajouter un nouveau chapitre :

1. Ouvrez `src/SUMMARY.md` dans votre éditeur de texte.
2. Ajoutez une nouvelle entrée pour votre chapitre à l'endroit souhaité dans la structure du livre :
    ```markdown
    - [Nom de votre chapitre](chemin-vers-chapitre.md)
    ```

3. Si le fichier Markdown mentionné n'existe pas encore, mdBook le créera automatiquement la prochaine fois que vous servirez ou compilerez le livre.

### Générer le livre pour la publication

Pour générer la version HTML de votre livre prête à être publiée sur un serveur :

```bash
mdbook build
```

Cette commande créera un dossier `book/` contenant les fichiers HTML. Vous pouvez ensuite déployer ce dossier sur n'importe quel serveur web.

### Configuration

Les paramètres du livre se trouvent dans le fichier `book.toml`. Ce fichier permet de configurer le titre, les langues prises en charge, et d'autres options relatives à la construction du livre.

Exemple de configuration minimaliste :
```toml
[book]
title = "Devenir une IT Woman"
author = ["Kevin Delfour", "Houleymatou Baldé"]
```

Pour plus de détails sur la configuration possible, consultez la [documentation officielle de mdBook](https://rust-lang.github.io/mdBook/).

---

## Contribution

Nous encourageons les contributions à ce projet ! Si vous souhaitez soumettre une suggestion, ajouter du contenu ou corriger des erreurs, n'hésitez pas à ouvrir une issue ou à soumettre une pull request.

### Cloner le dépôt

```bash
git clone git@github.com:yeeso-lyon/Ebook_Devenir_IT_Woman.git
cd Ebook_Devenir_IT_Woman
```

### Mettre à jour le contenu

Vous pouvez modifier les fichiers Markdown situés dans le dossier `src/` et les visualiser localement avec la commande `mdbook serve` (voir la section [Lancer le livre en local](#lancer-le-livre-en-local)).

---

## Licence

Ce projet est sous licence [Nom de la licence].

---

## Ressources supplémentaires

- [mdBook Documentation](https://rust-lang.github.io/mdBook/)
- [Rust Programming Language](https://www.rust-lang.org/)