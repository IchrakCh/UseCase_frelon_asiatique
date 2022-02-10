
# Installation

```bash
git clone 
pip install -r yolov5/requirements.txt  # installation des librairies utilisées
```

# Modèle utilisé : 

Yolov5 

Yolo est un modèle de réseau de neurone utilisé pour la détection et la classification d'objet dans une image. Il permet d'identifier l'objet en générant une bounding box autour et de le classifier suivant les classes données à l'entrainement.

# Sources :

### Bibliothèque utilisée : 

Nous avons utilisé le repository de <a href="https://ultralytics.com">Ultralytics</a> mis à jour le 25 janvier 2022.

### Labélisation des données :

Nous avons utilisé RoboFlow pour taguer et augmenter les données. Ces dernières sont ensuite importées via une clé API.

### Données : 

1ere classe: Frelon Asiatique Vespa Velutina

2eme classe: Frelon Européen

3eme classe: Autres (abeilles, mouches, guêpes)
