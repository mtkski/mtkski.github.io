Ceci sont les tâches détaillées par Raoul Someillier, maitre de stage, à l'approche du début de celui-ci. 

# Projet 1 : AI, communication inter/intraspécifique et visualisation
Il s'agit d'un projet de R&D et de soutien technique en collaboration avec l'artiste [Antoine Bertin](https://www.studioantoinebertin.com/) qui est en résidence chez nous.  
Les collaborateurs scientifiques sont des chercheurs du [Earth Species Project](https://www.earthspecies.org/) (ESP), issus de diverses universités (surtout américaines). L'intention de leur travail de recherche est bien synthétiser sur leur site:

_"Our work to decode communication of other species builds on the extraordinary advances we are seeing in AI being applied to human language, which we are extending to the non-human world.  
It also builds off many decades of bioacoustics and behavioral ecology research which has already uncovered complex communication systems in other species.  
The machine learning models we are building are also supporting and deepening ongoing research into the behavior of other species and advancing conservation efforts on the ground today."_  

Dans le cadre de notre collaboration, on s'intéresse surtout à la communication entre mammifères marins, en particulier des belugas.  
L'objectif est donc d'enregistrer une grande quantité de "discussions" entre belugas (par exemple entre une mère et son petit) et d'utiliser ces enregistrements audio comme data en input de modèles de machine learning (dans la même idée que des modèles de langage type ChatGPT mais pour la communication animale, donc sans la possibilité de transcrire en format texte). L'objectif ultime est donc de tenter de comprendre ce que les belugas se racontent. Mais avant ça, il faut faire de l'analyse audio pour déterminer les diverses dimensions impliquées, réduire la dimensionalité et compléter ce travail par des analyses comportementales.  
Un modèle développé par les chercheurs de ESP est AVES (Animal Vocalization Encoder based on Self-Supervision) : _"a self-supervised, transformer-based audio representation model for encoding animal vocalizations ("BERT for animals")"_.


__La mission du Ohme Lab__ dans ce projet est de :

- Se baser sur les travaux de ESP pour développer un code permettant d'analyser des vocalisations de beluga (dans un premier temps, peut-être aussi d'autres animaux par la suite, à voir).
- Visualiser le résultat de cette analyse, dans le sens de "rendre visuel" sur base de critères esthétiques définis avec Antoine Bertin.
- A noter que nous faisons aussi toujours attention au sens et à la vocation pédagogique de nos projets. Il s'agit donc également de faire en sorte que ces visualisations puissent être utilisées comme base pour expliquer des phénomènes scientifiques au grand public.
- Modéliser ces visualisations afin de réaliser des sculptures tridimensionnelles (via impression 3D ou autre méthode de prototypage et de fabrication)

# Projet 2 : Biométrie, interactivité et rétroaction entre oeuvres et réactions humaines
Ce projet s'inscrit dans un axe de R&D interne à Ohme qui vise à créer des boucles de rétroaction entre une oeuvre (installation d'art numérique, composition musicale, performance ou autre) et les réactions physiologiques, sensorielles, mentales et émotionnelles de la personne qui en fait l'expérience (spectateur ou performeur).  
En d'autres termes, il s'agit de concevoir des œuvres qui provoquent des réactions humaines, de développer des technologies permettant de mesurer ces réactions, et d'utiliser ces mesures pour faire évoluer l'œuvre de façon dynamique et en temps réel.

L'idée est donc :
- de développer des capteurs biométriques (ou adapter/hacker des technologies déjà existantes) servant à mesurer les réactions physiologiques humaines. Quelques exemples de capteurs : casque EEG pour mesurer les rythmes cérébraux, capteur de pression pour les pas, caméra depthsensing pour les déplacements, ECG pour les battements du coeur, etc.).
- d'envoyer ces signaux de mesure en wireless à un PC.
- de filter et d'analyser ces mesures pour en déduire des variations sur les états mentaux et/ou émotionnels des personnes qui portent ces capteurs biométriques.
- de visualiser ces variations afin qu'elles fassent partie intégrante de l'œuvre et/ou d'utiliser ces variations pour faire évoluer l'œuvre (au niveau sonore, visuel, cinétique ou autre).
- Ces "évolutions" de l'oeuvre peuvent soit renforcer le changement d'état de la personne (rétroaction positive), soit l'atténuer (rétroaction négative). Avec toujours comme volonté que cela nous permette d'utiliser cette expérience vécue par le spectateur comme un moyen de mieux comprendre et d'acquérir de nouvelles connaissances (sur le fonctionnement de notre cerveau, de nos émotions, des technologies employées, etc.)

Comme décrit dans ta convention de stage, les missions concernent 3 volets :

- Le développement d'une boîte à outils software et hardware capable de recevoir en input une grande quantité de signaux provenant de capteurs biométriques et environnementaux.
- Le développement d'un modèle AI de classification capable de déterminer en temps réel les (variations d') états émotionnels et mentaux d'une (ou plusieurs) personnes sur base des mesures prises par des capteurs biométriques.  
- La visualisation et la sonification des signaux (input et output), ce qui requiert la compatibilité des systèmes de mesure, d'instrumentation et d'analyse placés en amont avec des logiciels de création et d'art numérique tel que TouchDesigner.
- _Contraintes importantes_ : l'entièreté de la chaîne doit pouvoir s'adapter à la personne qui en fait l'expérience, le fonctionnement doit être (quasi) temps-réel et l'installation doit se faire très rapidement (idéalement sans besoin d'un assistant ou médiateur).

