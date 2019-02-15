# EGSS-Data-Analysis

Electrical Grid Stability Simulated Data Modeling and Analysis

Data Set Information : [Electrical Grid Stability Simulated Data](https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+)

Ce dataset permet l'analyse de la stabilité locale d’un système en étoile à 4 nœuds (le producteur d'électricité est au centre) mettant en œuvre le concept de contrôle de réseau intelligent décentralisé (Decentral Smart Grid Control).

11 attributs prédictifs, 1 non prédictif (p1), 2 champs d’objectif :
  tau[x] : temps de réaction du participant (réel dans l'intervalle [0.5 ;10] s).
 	   Tau1 - la valeur pour le producteur d'électricité.
  p[x] : puissance nominale consommée (négative) / produite (positive) (réelle).
	   Pour les consommateurs de la plage [-0,5 ; -2] s ^ -2;
	   p1 = abs (p2 + p3 + p4)
  g[x] : coefficient (gamma) proportionnel à l'élasticité des prix (réel de l'intervalle [0.05 ; 1] s ^ -1).
	   g1 = la valeur pour le producteur d'électricité.
  Stab : la partie réelle maximale de la racine de l’équation caractéristique (si positive - le système est linéairement instable) (réel)
  Stabf : l’étiquette de stabilité du système (catégorique: stable / instable)

Nous avons choisi de faire une classification du champ « Stabf » pour savoir si c’est stable ou instable.

## Getting Started

These instructions below will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

<!-- Your Redis Database must be running.
This program will request on Local Redis on default port.
You need to have [Node.js](https://nodejs.org/en/) installed with a package manager like [NPM](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/).

You can check it up by running this command in your console :

```
node -v
``` -->

### Installing

To install all the packages needed by this project, you have to run an packager manager.

<!-- Run this command if you are using [NPM](https://www.npmjs.com/):

```
npm install
```

Or this command if you are using [Yarn](https://yarnpkg.com/):

```
yarn install
``` -->

## Running locally the code.

<!-- To run this servers locally please use this command: -->

```
```

<!-- The server will be running on port 8080. -->

<!-- ## Deployment -->

<!-- ## Contributing -->

<!-- ## Versioning -->

## Authors

* **Shengda Liu** - *Initial work* - [shengdaliu](https://github.com/shengdaliu)
* **Matthias Exbrayat** - *Initial works* - [MatthiasExbrayat](https://github.com/MatthiasExbrayat)

## License

This project is not licenced.

<!-- ## Acknowledgments -->
