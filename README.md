![Spatter detection](spatter.gif "Spatter examples")

- [spatter-tracking](#spatter-tracking)
  * [Description](#description)
    + [Methodes classiques](#methodes-classiques)
    + [Deep Learning](#deep-learning)
  * [Articles](#articles)
    + [Detection d'ejectas (computer vision)](#detection-d-ejectas--computer-vision-)
      - [Types of spatter and their features and formation mechanisms in laser powder bed fusion additive manufacturing process](#types-of-spatter-and-their-features-and-formation-mechanisms-in-laser-powder-bed-fusion-additive-manufacturing-process)
        * [Lien](#lien)
        * [Resume](#resume)
    + [Detection d'ejectas (deep learning)](#detection-d-ejectas--deep-learning-)
      - [A novel spatter detection algorithm based on typical cellular neural network operations for laser beam welding processes](#a-novel-spatter-detection-algorithm-based-on-typical-cellular-neural-network-operations-for-laser-beam-welding-processes)
        * [Resume](#resume-1)
      - [Neural network based image segmentation for spatter extraction during laser-based powder bed fusion processing](#neural-network-based-image-segmentation-for-spatter-extraction-during-laser-based-powder-bed-fusion-processing)
        * [Lien](#lien-1)
        * [Resume](#resume-2)
      - [A deep learning-based model for defect detection in laser-powder bed fusion using in-situ thermographic monitoring](#a-deep-learning-based-model-for-defect-detection-in-laser-powder-bed-fusion-using-in-situ-thermographic-monitoring)
        * [Lien](#lien-2)
        * [Resume](#resume-3)
    + [Analyse granulometrique](#analyse-granulometrique)
      - [Image-based size analysis of agglomerated and partially sintered particles via convolutional neural networks](#image-based-size-analysis-of-agglomerated-and-partially-sintered-particles-via-convolutional-neural-networks)
        * [Lien](#lien-3)
        * [Resume](#resume-4)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# spatter-tracking

## Description 

Ce site comprend un état de l'art des techniques de deep learning appliquées au tracking d'éjectas en fabrication additive par lit de poudre ainsi
que l'application de techniques de deep learning à l'analyse granulométrique des poudres.

### Methodes classiques 

[ImageJ](https://fr.wikipedia.org/wiki/ImageJ) (_Image Analysis and Processing in Java_) est souvent utilisé dans le monde des matériaux comme outil d'analyse d'images. Néanmoins, ImageJ (et les autres logiciels commerciaux) embarquent rarement
des fonctionnalités de deep learning car celles-ci sont rarement généralistes et difficilement réglables. Néanmoins, dans beaucoup de situations l'utilisation de technique de deep learning semble permettre de gagner en performance par rapport à des techniques de traitement d'images plus bas niveau.

![Example](https://www.fzu.cz/~dominecf/granulo/img/particles_found.png)



### Deep Learning

[DeepImageJ](https://deepimagej.github.io/deepimagej/index.html) montre quelques applications récente de deep learning sur du traitement d'image issue des sciences des matériaux et des sciences de la vie.

![DeepImageJ](https://deepimagej.github.io/deepimagej/images/deepimagej_logo.png)


## Articles

### Detection d'ejectas (computer vision)

#### Types of spatter and their features and formation mechanisms in laser powder bed fusion additive manufacturing process

![Spatter types](https://ars.els-cdn.com/content/image/1-s2.0-S2214860420308101-gr6.jpg)

##### Lien

[Zachary A. Young, Qilin Guo, Niranjan D. Parab, Cang Zhao, Minglei Qu, Luis I. Escano, Kamel Fezzaa, Wes Everhart, Tao Sun, Lianyi Chen,
Types of spatter and their features and formation mechanisms in laser powder bed fusion additive manufacturing process,
Additive Manufacturing,
2020,
101438,
ISSN 2214-8604,
https://doi.org/10.1016/j.addma.2020.101438](https://www.sciencedirect.com/science/article/pii/S2214860420308101)

##### Resume

En fabrication additive par fusion laser sur lit de poudre (LPBF), les éjectas provoquent la formation de défauts, la redistribution non-uniforme de la poudre et la contamination du processus. Il est essentiel de distinguer les différents types d'éjectas et de comprendre leurs caractéristiques et leurs mécanismes de formation. Ce travail révèle les caractéristiques et les mécanismes de formation de cinq types uniques d'éjectas au cours du processus de LPBF par imagerie radiographique in situ à haute vitesse et haute énergie. Les éjectas observés pendant le test LPBF sont quantifiés par leur vitesse, leur taille et leur direction. Des caractéristiques quantifiables distinctes pour chaque type d'éjectas sont identifiées. Les effets de la puissance du laser, de la vitesse de balayage et de la pression ambiante sur la formation et les caractéristiques des éjectas sont mis en évidence. Une carte de formation des éjectas pour l'alliage AlSi10Mg est établie.


### Detection d'ejectas (deep learning)

#### A novel spatter detection algorithm based on typical cellular neural network operations for laser beam welding processes

![CNN for spatter detection](https://cdn.iopscience.com/images/0957-0233/23/1/015401/Full/mst405576fig04.jpg)

##### Resume 

La surveillance en temps réel du soudage par faisceau laser (LBW) a pris une importance croissante dans de nombreux procédés de fabrication allant de la production automobile à la mécanique de précision. Dans cette dernière, un nouvel algorithme de détection en temps réel des éjectas est mis en œuvre à l'aide une caméra et des réseaux neuronaux cellulaires. Cette dernière peut être connectée à des machines laser disponibles dans le commerce via leurs capteurs optiques, ce qui permet de surveiller en temps réel les procédés de soudage par faisceaux laser à des fréquences allant jusqu'à 15 kHz. Ces fréquences élevées permettent l'intégration d'autres tâches de surveillance telles que la détection du trou de pénétration complet pour le contrôle en temps réel des paramètres du processus.

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

##### Resume 

Un système de détection et de surveillance in situ des éjectas est souvent utilisée pour améliorer la qualité des produits lors de la fusion du lit de poudre par laser (LPBF). Cet article décrit une nouvelle méthode de segmentation d'images basée sur les réseaux de neurones (NN) pour l'extraction des éclaboussures avec un processus de marquage simple et des résultats de haute précision. L'utilisation d'une caméra à grande vitesse à bande d'ondes de 290-1100 nm a permis de capturer des images avec des signatures de projections plus complètes et un arrière-plan plus complexe par rapport aux études précédentes sur la fusion en lit de poudre par laser. Les approches conventionnelles de segmentation d'images ne permettent pas d'effectuer l'extraction des éclaboussures en raison de la complexité du fond. La méthode de segmentation d'images proposée, basée sur le réseau neuronal, divise les images en une grille de blocs et segmente chaque bloc en utilisant un réseau neuronal convolutif parallèle (CNN) et un réseau neuronal à seuil (TNN), ce qui permet d'extraire 80,48 % des éclaboussures en seulement 70 ms. En outre, la capacité d'extraire les éclaboussures liées à un bassin en fusion distingue la méthode de segmentation d'images proposée, basée sur le CNN, des approches de segmentation d'images conventionnelles.



#### A deep learning-based model for defect detection in laser-powder bed fusion using in-situ thermographic monitoring

![Detection de defaut](https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs40964-019-00108-3/MediaObjects/40964_2019_108_Fig1_HTML.png?as=webp)

##### Lien

[Baumgartl, Hermann, Tomas, Josef, Buettner, Ricardo, Merkel, Markus
A deep learning-based model for defect detection in laser-powder bed fusion using in-situ thermographic monitoring,
2020, Progress in Additive Manufacturing](https://link.springer.com/article/10.1007/s40964-019-00108-3)

##### Resume 
La fabrication additive de composants métalliques par fusion laser en lit de poudre est un processus très complexe, car la poudre doit être fondue et refroidie dans chaque couche pour produire une partie de la pièce. De nombreux paramètres influencent le processus d'impression ; cependant, les défauts résultant d'un réglage sous-optimal des paramètres sont généralement détectés après le processus. Pour détecter ces défauts pendant l'impression, différentes techniques de surveillance du processus, telles que la surveillance du bassin de fusion ou la surveillance infrarouge hors axe, ont été proposées. Dans ce travail, nous avons utilisé une combinaison d'imagerie thermographique hors axe comme source de données et d'architectures de réseau neuronal basées sur l'apprentissage profond, pour détecter les défauts d'impression. Pour la formation au réseau, une validation croisée avec k-plis et une validation croisée avec hold-out ont été utilisées. Grâce à ces techniques, des défauts tels que le délaminage et les éjectas peuvent être reconnus avec une précision de 96,80 %. En outre, le modèle a été évalué à l'aide de l'évaluation de la densité de calcul par couche. L'architecture est très petite et a de faibles coûts de calcul, ce qui signifie qu'elle est adaptée pour fonctionner en temps réel même sur du hardware peu puissant.

### Analyse granulometrique

#### Image-based size analysis of agglomerated and partially sintered particles via convolutional neural networks

![Analyse de poudre](https://ars.els-cdn.com/content/image/1-s2.0-S003259101930854X-ga1_lrg.jpg)

##### Lien

[M. Frei, F.E. Kruis,
Image-based size analysis of agglomerated and partially sintered particles via convolutional neural networks,
Powder Technology,
Volume 360,
2020,
Pages 324-336,](https://www.sciencedirect.com/science/article/pii/S003259101930854X)

##### Resume 

Il existe une forte demande de méthodes entièrement automatisées pour l'analyse des distributions granulométriques des particules primaires agglomérées ou frittées en raison de leur impact sur les propriétés des matériaux. C'est pourquoi une nouvelle méthode de détection de ces particules primaires, basée sur l' apprentissage profond, a été proposée et testée, ce qui rend inutile un réglage manuel des paramètres d'analyse de l'image dans les méthodes classiques.
L'entraînement des réseaux neuronaux convolutifs utilisés a été effectuée en utilisant uniquement des images synthétiques, évitant ainsi la tâche laborieuse de l'annotation manuelle et augmentant la qualité de la vérité de terrain. Néanmoins, la méthode proposée donne d'excellents résultats sur des échantillons réels de nanoparticules de silice frittée avec divers degrés de frittage et des conditions d'image variables.
En comparaison directe, la méthode proposée est nettement plus performante que deux méthodes avancées pour l'analyse granulométrique automatisée basée sur l'image (transformation de Hough et le plug-in ImageJ ParticleSizer), atteignant ainsi des performances comparables à celles d'un humain.
