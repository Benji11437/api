# Application ApiFast du projet 7
1. Presentation 

Il s'agit d'une application réalisée avec FastApi 
deployé sur Microsoft Azure web.
Le modèle analyse le sentiment associé à un texte (tweet)

L' appli consiste à predire le sentiment (positif ou negatif) associé à un tweet.
le modèle deployé ici est un modele de Regression Logistique.

L'utilisateur ecrit son texte sur l'interface, l'application reçoit le texte via la methode post, 
execute plusieurs traitements notemment le convertion du texte en anglais, le netoyage, la tokenisation,
la vectorisation du texte et enfin predit le sentiment qui resort de son analyse.
L'utilsateur confirme si oui ou non la prediction est bonne.


## Table of Contents

2. Technologies
Python 3.9
fastapi==0.111.0
fastapi-cli==0.0.4
deep-translator==1.11.4
nltk==3.8.1
uvicorn==0.29.0

3. Installation
git clone https://github.com/Benji11437/api.git

