Introduction
------------

Merci pour de prendre le temps de contribuer à ce projet communautaire pour promouvoir les sciences des surfaces planétaires à l'échelle de la communauté française.
Afin de garantir une certaine homogénéité dans la rédaction de ce guide, merci de suivre les recommandations suivantes.

Format et style
---------------

Les articles de ce guide sont rédigés principalement en français en suivant une syntaxe de type [markdown](https://fr.wikipedia.org/wiki/Markdown) (`.md`) et regroupé dans le dossier `docs/`.
Si vous n'êtes pas familier de ce language, vous pouvez consulter [ces quelques exemples](https://fr.wikipedia.org/wiki/Markdown#Quelques_exemples)
pour débuter facilement. Le markdown est le language natif de Github pour la soumission de modification depuis leur interface web.
N'hésitez pas à utiliser le bouton <kbd>preview</kbd> pour visualiser vos résultats.

Si le contenu de votre article s'y porte, vous pouvez le rédiger directement en [jupyter-notebooks](https://jupyterbook.org/file-types/notebooks.html) (`.ipynb`).

L'ensemble des articles est reformaté grace à [Jupyter-Book](https://jupyterbook.org) et Github pour être afficher sur la [page web du pole des surfaces planétaires](https://pole-surfaces-planetaires.github.io).


Soumettre un changement, proposer une modification ou un ajout
--------------------------------------------------------------

1. Faite un _fork_ de ce dépôt pour l'ajouter à votre espace Github en cliquant [ici](https://github.com/pole-surfaces-planetaires/pole-surfaces-planetaires.github.io/fork).
2. Ajoutez et modifier un article à la fois, directement en ligne sur Github ou localement (cf. section ci-dessous). Si c'est votre première contribution pensez à ajouter votre nom dans la liste des `AUTHORS.md`.
3. Soumettez une _Pull Request_ avec vos ajouts sur le projet.
4. Les modifications seront validées manuellement par l'un des membres du pole.
5. Le guide en ligne sera mis à jour automatiquement avec votre nouvel article :rocket:


Modifier ce guide localement
----------------------------

Pour modifier le guide localement, commencez par récupérer une copie du projet (après l'avoir _forké_):

```bash
git clone https://github.com/<GH_USERNAME>/pole-surfaces-planetaires.github.io
cd pole-surfaces-planetaires.github.io
```

Faites vos modifications dans le dossier `docs/`.

Si vous voulez visualiser le rendu de votre article avant de le soumettre, vous pouvez installer les dépendances du projet:

```bash
pip install -r requirements.txt
```

Puis exécuter la commande:

```bash
jupyter-book build docs/mon-article.md
```
