# segmentation-d-image

Ce projet utilise un modèle pré-entraîné Faster R-CNN avec ResNet50, disponible via torchvision, pour détecter et segmenter des objets dans des images. Les images sont traitées en tant que tenseurs, passées au modèle, et les résultats (bounding boxes, classes, scores) sont filtrés en fonction d'un seuil de confiance. Les objets détectés sont visualisés avec des cadres et des étiquettes sur l'image d'origine grâce à OpenCV et Matplotlib. Ce pipeline est conçu pour être flexible et performant, tout en permettant des ajustements pour améliorer la lisibilité et l'efficacité des résultats.

lien vers le Notion: https://www.notion.so/Projet-Segmentation-d-objets-8fa8a7c4b82444fe94c135268050e304?pvs=4
