
# YOLOV5

# Installation

```bash
git clone https://github.com/IchrakCh/UseCase_frelon_asiatique.git
pip install -r yolov5/requirements.txt  # installation des librairies utilisées
```

# Modèle utilisé : 

Yolov5 

Yolo est un modèle de réseau de neurone utilisé pour la détection et la classification d'objet dans une image. Il permet d'identifier l'objet en générant une bounding box autour et de le classifier suivant les classes données à l'entrainement.

# Sources :

### Bibliothèque utilisée : 

Nous avons utilisé le repository de <a href="https://ultralytics.com">Ultralytics</a> mis à jour le 25 janvier 2022 disponible <a href="https://github.com/ultralytics/yolov5">ici</a>.

### Labélisation des données :

Nous avons utilisé <a href="https://roboflow.com/">RoboFlow</a> pour taguer et augmenter les données. Ces dernières sont ensuite importées via une clé API.

### Données : 

1ere classe: Frelon Asiatique Vespa Velutina

2eme classe: Frelon Européen

3eme classe: Autres (abeilles, mouches, guêpes)


# VGG16

# Modèle utilisé : 

VGG16

VGG est un réseau de neurones convolutionnels qui a atteint une précision de 92.7% sur Imagenet ce qui est un des meilleurs scores obtenus. C'est un algorithme connu très souvent utilisé par transfert d’apprentissage pour éviter d’avoir à le réentraîner et résoudre des problématiques proches sur lesquelles VGG a déjà été entraîné.


# Sources :

### Données : 

1ere classe: Frelon Asiatique Vespa Velutina

2eme classe: Frelon Européen

3eme classe: Autres (abeilles, mouches, guêpes)


