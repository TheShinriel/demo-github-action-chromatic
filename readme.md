# Demo d'une Github action pour Chromatic

Ce repository se base sur le [template](https://github.com/chromaui/intro-storybook-react-template) proposé par CHromatic.

Ce projet propose un exemple pratique de l'utilisation de GitHub Actions en combinaison avec Chromatic pour visualiser les évolutions de Storybook d'un commit à l'autre. Storybook est une plateforme open-source permettant de développer, tester et documenter des composants d'interface utilisateur de manière isolée. Pour en savoir plus sur Storybook, vous pouvez consulter [ce tutoriel](https://storybook.js.org/tutorials/intro-to-storybook/react/fr/get-started/).

Chromatic, quant à lui, est un outil puissant qui permet de visualiser les changements visuels dans votre application web à chaque commit. Pour en savoir plus sur Chromatic et ses fonctionnalités, vous pouvez consulter la documentation [ici](https://www.chromatic.com/docs/).

## Utilisation

1. Forkez ce dépôt vers votre compte GitHub.

2. Configurez votre propre application Storybook dans le répertoire et assurez-vous que le fichier `.chromatic.js` est présent à la racine.

3. Dans le dossier `.github/workflows`, vous trouverez un fichier nommé `chromatic.yml`. Ce fichier définit le workflow GitHub Actions pour Chromatic.

3a. Pour s'assurer que le script fonctionne, il faudra ajouter un `secrets` => `CHROMATIC_PROJECT_TOKEN`
3b. Une fois créé un compte chez [chromatic](https://www.chromatic.com/docs/), et créé un token pour le projet, il vous faut l'ajouter 

4. Lorsque vous effectuez des commits dans ce projet, le workflow GitHub Actions pour Chromatic sera déclenché automatiquement. Vous pourrez voir les changements visuels dans vos composants Storybook à chaque commit et gérer les évolutions graphiques de manière efficace.

## Formation sur GitHub Actions

Ce projet fait partit d'une formation sur l'utilisation de GitHub Actions et découvrir comment automatiser vos intégrations continues sur Udemy : [Automatiser tout sur vos projets avec Github Actions](https://www.udemy.com/course/automatiser-tout-sur-vos-projets-avec-github-actions/?referralCode=268A353A1CAE10611EBD).

N'hésitez pas à explorer les fonctionnalités de Chromatic et de Storybook pour améliorer la qualité et la robustesse de vos composants d'interface utilisateur. Happy coding! 🚀

