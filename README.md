<h2 align="center"> 🧮 Calculatrice JavaScript </h2>

<p>Ce projet est une calculatrice simple réalisée en JavaScript pour gérer les interactions de l'utilisateur via le clavier et la souris.<p>

<h2 align="center"> 🎯 Fonctionnalités </h2>

- **Saisie au clavier** : Entrez des valeurs en utilisant les touches de votre clavier.
- **Saisie à la souris** : Cliquez sur les boutons de la calculatrice pour entrer des valeurs.
- **Effacement** : La touche avec le code `8` permet d'effacer l'écran.
- **Évaluation du calcul** : La touche avec le code `13` (Entrée) évalue l'expression mathématique affichée à l'écran.

<h2 align="center"> 🛠️ Détails du code </h2>

- Les boutons de la calculatrice sont sélectionnés avec `document.querySelectorAll('.bouton')`.
- Chaque bouton possède un attribut `data-key` utilisé pour identifier l'action associée.
- Les événements `keydown` (pour la saisie au clavier) et `click` (pour la saisie à la souris) déclenchent la fonction `calculer(valeur)` qui gère la logique de la calculatrice.
- En cas d'erreur lors de l'évaluation de l'expression (par exemple, une division par zéro), un message d'alerte est affiché grâce à l'événement `error` de la fenêtre.

<h2 align="center"> 🚀 Lien </h2>
https://faudotrina.github.io/calculatrice/
