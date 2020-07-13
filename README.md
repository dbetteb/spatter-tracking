- [spatter-tracking](#spatter-tracking)
  * [Description](#description)
    + [Méthodes classiques](#m-thodes-classiques)
    + [Deep Learning](#deep-learning)
  * [Références](#r-f-rences)
    + [Tracking d'éjectas](#tracking-d--jectas)
      - [Neural network based image segmentation for spatter extraction during laser-based powder bed fusion processing](#neural-network-based-image-segmentation-for-spatter-extraction-during-laser-based-powder-bed-fusion-processing)
        * [Lien](#lien)
        * [Résumé](#r-sum-)
      - [A deep learning-based model for defect detection in laser-powder bed fusion using in-situ thermographic monitoring](#a-deep-learning-based-model-for-defect-detection-in-laser-powder-bed-fusion-using-in-situ-thermographic-monitoring)
        * [Lien](#lien-1)
        * [Résumé](#r-sum--1)
    + [Analyse granulométrique](#analyse-granulom-trique)
      - [Image-based size analysis of agglomerated and partially sintered particles via convolutional neural networks](#image-based-size-analysis-of-agglomerated-and-partially-sintered-particles-via-convolutional-neural-networks)
        * [Lien](#lien-2)
        * [Résumé](#r-sum--2)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

![Spatter detection](https://ars.els-cdn.com/content/image/1-s2.0-S0030399220309804-gr5.jpg "Spatter examples")


# spatter-tracking

## Description 

Ce site comprend un état de l'art des techniques de deep learning appliquées au tracking d'éjectas en fabrication additive par lit de poudre ainsi
que l'application de techniques de deep learning à l'analyse granulométrique des poudres.

### Méthodes classiques

ImageJ

### Deep Learning



## Références

### Tracking d'éjectas

#### Neural network based image segmentation for spatter extraction during laser-based powder bed fusion processing

![Spatter detection](https://ars.els-cdn.com/content/image/1-s2.0-S0030399220309804-gr5.jpg "Spatter detection")

##### Lien

[Zhenbiao Tan, Qihang Fang, Hui Li, Sheng Liu, Wenkang Zhu, Dekun Yang,
Neural network based image segmentation for spatter extraction during laser-based powder bed fusion processing,
Optics & Laser Technology,
Volume 130,
2020,
106347,
ISSN 0030-3992](https://www.sciencedirect.com/science/article/pii/S0030399220309804?dgcid=rss_sd_all)

##### Résumé 

Un système de détection et de surveillance in situ des éjectas est souvent utilisée pour améliorer la qualité des produits lors de la fusion du lit de poudre par laser (LPBF). Cet article décrit une nouvelle méthode de segmentation d'images basée sur les réseaux de neurones (NN) pour l'extraction des éclaboussures avec un processus de marquage simple et des résultats de haute précision. L'utilisation d'une caméra à grande vitesse à bande d'ondes de 290-1100 nm a permis de capturer des images avec des signatures de projections plus complètes et un arrière-plan plus complexe par rapport aux études précédentes sur la fusion en lit de poudre par laser. Les approches conventionnelles de segmentation d'images ne permettent pas d'effectuer l'extraction des éclaboussures en raison de la complexité du fond. La méthode de segmentation d'images proposée, basée sur le réseau neuronal, divise les images en une grille de blocs et segmente chaque bloc en utilisant un réseau neuronal convolutif parallèle (CNN) et un réseau neuronal à seuil (TNN), ce qui permet d'extraire 80,48 % des éclaboussures en seulement 70 ms. En outre, la capacité d'extraire les éclaboussures liées à un bassin en fusion distingue la méthode de segmentation d'images proposée, basée sur le CNN, des approches de segmentation d'images conventionnelles.



#### A deep learning-based model for defect detection in laser-powder bed fusion using in-situ thermographic monitoring

![Detection de defaut](https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs40964-019-00108-3/MediaObjects/40964_2019_108_Fig1_HTML.png?as=webp)

##### Lien

[Baumgartl, Hermann, Tomas, Josef, Buettner, Ricardo, Merkel, Markus
A deep learning-based model for defect detection in laser-powder bed fusion using in-situ thermographic monitoring,
2020, Progress in Additive Manufacturing](https://link.springer.com/article/10.1007/s40964-019-00108-3)

##### Résumé 
La fabrication additive de composants métalliques par fusion laser en lit de poudre est un processus très complexe, car la poudre doit être fondue et refroidie dans chaque couche pour produire une partie de la pièce. De nombreux paramètres influencent le processus d'impression ; cependant, les défauts résultant d'un réglage sous-optimal des paramètres sont généralement détectés après le processus. Pour détecter ces défauts pendant l'impression, différentes techniques de surveillance du processus, telles que la surveillance du bassin de fusion ou la surveillance infrarouge hors axe, ont été proposées. Dans ce travail, nous avons utilisé une combinaison d'imagerie thermographique hors axe comme source de données et d'architectures de réseau neuronal basées sur l'apprentissage profond, pour détecter les défauts d'impression. Pour la formation au réseau, une validation croisée avec k-plis et une validation croisée avec hold-out ont été utilisées. Grâce à ces techniques, des défauts tels que le délaminage et les éjectas peuvent être reconnus avec une précision de 96,80 %. En outre, le modèle a été évalué à l'aide de l'évaluation de la densité de calcul par couche. L'architecture est très petite et a de faibles coûts de calcul, ce qui signifie qu'elle est adaptée pour fonctionner en temps réel même sur du hardware peu puissant.

### Analyse granulométrique

#### Image-based size analysis of agglomerated and partially sintered particles via convolutional neural networks

##### Lien

[M. Frei, F.E. Kruis,
Image-based size analysis of agglomerated and partially sintered particles via convolutional neural networks,
Powder Technology,
Volume 360,
2020,
Pages 324-336,](https://www.sciencedirect.com/science/article/pii/S003259101930854X)

##### Résumé 

Il existe une forte demande de méthodes entièrement automatisées pour l'analyse des distributions granulométriques des particules primaires agglomérées ou frittées en raison de leur impact sur les propriétés des matériaux. C'est pourquoi une nouvelle méthode de détection de ces particules primaires, basée sur l' apprentissage profond, a été proposée et testée, ce qui rend inutile un réglage manuel des paramètres d'analyse de l'image dans les méthodes classiques.
L'entraînement des réseaux neuronaux convolutifs utilisés a été effectuée en utilisant uniquement des images synthétiques, évitant ainsi la tâche laborieuse de l'annotation manuelle et augmentant la qualité de la vérité de terrain. Néanmoins, la méthode proposée donne d'excellents résultats sur des échantillons réels de nanoparticules de silice frittée avec divers degrés de frittage et des conditions d'image variables.
En comparaison directe, la méthode proposée est nettement plus performante que deux méthodes avancées pour l'analyse granulométrique automatisée basée sur l'image (transformation de Hough et le plug-in ImageJ ParticleSizer), atteignant ainsi des performances comparables à celles d'un humain.
