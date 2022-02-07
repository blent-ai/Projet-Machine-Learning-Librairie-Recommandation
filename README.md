<div align="center">
  <a href="https://blent.ai">
    <img src="https://blent-static-media.s3.eu-west-3.amazonaws.com/images/logo/logo_blent_300x.png" alt="Logo Blent.ai" width="200" />
  </a>

  <h2 align="center">Service de recommandation pour une librairie en ligne</h2>

  <p align="center">
    Projet Computer Vision - <a href="https://blent.ai">Blent.ai</a>
    <br />
    <a href="https://blent.ai/app/projects" target="_blank"><strong>Explorer tous les projets »</strong></a>
</div>

<div align="center"><img src="https://cdn.static-media.blent.ai/images/projects/badge_books.svg" width="120" alt="Badge du projet" /></div>

## À propos du projet

Afin d'optimiser le parcours d'achat de ses clients, une librairie en ligne souhaite **proposer des recommandations adaptées aux profils et aux expériences** passées de ses clients. Pour cela, elle cherche à utiliser les avis de ses clients sur l'ensemble de son répertoire pour conseiller des lectures à ces derniers.

Ce service sera déployé sur l'infrastructure Cloud de l'entreprise, et sera utilisé aussi bien pour des opérations « à froid » (campagnes d'emails avec recommandations) ou « à chaud » (recommandation pendant la visite sur le site). L'entreprise utilise des **informations connues sur ses clients**, en particulier les notes qu'ils ont attribués à des précédentes lectures, afin de déterminer quelles seront les prochains ouvrages que ces derniers seront susceptibles d'apprécier. Elle pourra ensuite afficher les $n$ premiers livres dont les notes estimées sont les plus élevées.

L'objectif est d'élaborer et entraîner un modèle qui sera **capable d'estimer une note** entre 1 et 10 à un livre en fonction de l'historique de l'utilisateur.

> TODO : Compléter cette partie pour apporter plus d'informations sur le contexte du projet.

## Étapes du projet

- [ ] Construire la matrice des observations
- [ ] Entraîner le système de recommandation sur un échantillon réduit
- [ ] Entraîner le système de recommandation sur un échantillon suffisamment grand
- [ ] Évaluer les performances du service
- [ ] Publier le code source et les résultats sur GitHub

La description des étapes est disponible sur la page associée au projet.

> TODO : Cocher les cases au fur et à mesure de l'avancement.

## Résultats

| Taille du train |      Précision      |     Sensibilité     |
|:---------------:|:-------------------:|:-------------------:|
|        1k       | 00.00% ± 00.00% | 00.00% ± 00.00% |
|       10k       | 00.00% ± 00.00% | 00.00% ± 00.00% |
|       100k      | 00.00% ± 00.00% | 00.00% ± 00.00% |

> TODO : Il est possible d'ajouter des graphes pour apporter plus d'indications sur les résultats.

## Structure du projet

Le dépôt Git contient les éléments suivantes.

- `notebooks/` contient les Notebooks Jupyter du projet.
- `src/` contient les codes sources Python principaux du projet.
- `data/` contient les données du projet.
- `config/` contient les configurations et paramètres du projet.
- `LICENSE.txt` : licence du projet.
- `requirements.txt` : liste des dépendances Python nécessaires.
- `README.md` : fichier d'accueil.

## Premiers pas

Les instructions suivantes permettent d'exécuter le projet sur son PC.

### Pré-requis

Le projet nécessite Python 3 d'installé sur le système.

> TODO : Ne pas hésiter à compléter/adapter cette partie en fonction des dépendances logicielles.

### Installation

1. Cloner le projet Git.
	```
	git clone https://github.com/blent-ai/Projet-Machine-Learning-IRM-Cerveaux.git
	```
2. Installer les dépendances du fichier `requirements.txt` dans un environnement virtuel.

	**Linux / MacOS**
	```
	python3 -m venv venv/
	source venv/bin/activate
	pip install -r requirements.txt
	```
	**Windows**
	```
	python3 -m venv venv/
	C:\<chemin_dossir>\venv\Scripts\activate.bat
	pip install -r requirements.txt
	```

> TODO :
> - Remplir le fichier `requirements.txt` pour y ajouter les dépendances.
> - Compléter la procédure d'installation pour l'adapter en fonction des besoins (GPU, librairies externes).

### Démarrage

> TODO : Expliquer en quelques lignes et avec des exemples de ligne de commande comment l'utilisateur peut entraîner ou utiliser lui-même le modèle. 

## Licence

*Ce projet est proposé par <a href="https://blent.ai">Blent.ai</a>. Les données utilisées pour ce projet peuvent être soumises à des droits d'auteur et de propriété intellectuelle. Blent.ai ne peut être responsable des utilisations faites des données utilisées dans le cadre de ce projet.*

> TODO : Ajouter les licences supplémentaires au projet (autres données, outils propriétaires, etc).

## Citations


