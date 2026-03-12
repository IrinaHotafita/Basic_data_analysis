# Basic_data_analysis

(Pour ceux qui n'ont jamais utilisé GitHub : pour télécharger le projet, cliquez sur < > Code et choisissez “Download ZIP”.)

## Sommaire

Le projet contient 2 dossiers principaux :

- data : contient 3 fichiers .csv de données de capteurs, utilisés à titre d’exemple.
  
- scripts : contient :
  
      deux scripts
  
         - quelques exemples de prétraitement des données
  
         - quelques exemples de visualisations (figures)
  
         - un sous-dossier utils : modules supplémentaires utilisés par les scripts pour éviter la répétition de code.

## Si vous n'avez pas encore Jupyter notebook

Vous trouverez ci-dessous les instructions pour installer Python.

Installer python avec Anaconda : https://www.anaconda.com/download?utm_source=anacondadocs&utm_medium=documentation&utm_campaign=download&utm_content=installwindows

- Créer un environnement virtuel

Dans console Anaconda prompt
 
Conda create -n <Nom_Environnement> python=3.12                      " <Nom_Environnement>  est le nom d’environnement que vous choisissez. Par ex myenv ou EnvSimulation… "
 
Conda activate <Nom_Environnement>                                

- Installer les librairies
Pour cela il suffit d'ouvrir un prompt anaconda et installer les packages avec:


pip install jupyter

Puis installer les librairies suivantes : (ce sont les bases mais vous pourrez installer d'autres packages plus tard)

pip install numpy

pip install pandas

pip install scipy

pip install pytz

pip install matplotlib

pip install seaborn

pip install plotly

pip install scikit-learn

pip install tensorflow

- Descriptions :
  
Python est juste un langage.

Les librairies sont les outils (écrit en Python)

 

- Manipulation de données
  
pandas => Manipulation de données (tableau ou DataFrame)

numpy => Calcul scientifique, tableaux multidimensionnels (arrays), algèbre linéaire

scipy => Calcul scientifique avancé (statistiques, etc.)

pytz => manipulation des dates

- Visualisation de données
  
matplotlib => Graphiques 2D

seaborn => Visualisations plus belle (basée sur matplotlib)

plotly => Graphiques interactifs

- Machine Learning et IA
  
scikit-learn => Machine learning classique (régression, classification, clustering)

tensorflow => Deep learning (LSTM,...)
