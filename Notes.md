# MOOC recherche reproductible 

## Week 1: Notes 1

### Chapitre 1: la reproductibilité est une notion complète

La reproductibilité est souvent réclamée comme la moindre des choses en science, et pourtant, en forçant un peu le trait, on pourrait avancer que quasiment rien n'est jamais reproduit : personne ne veut essayer, et quand quelqu'un essaye, ça ne marche pas. Ce qui est nouveau, c'est que cela semble rédhibitoire dans le cadre de bonnes pratiques scientifiques, au nom de la crédibilité de la science, et des initiatives pour y remédier commencent à fleurir.

La reproductibilité est aussi complexe parce que, bien que simple à imaginer en apparence, le concept recouvre tout un tas de pratiques qui posent des questions :  

* Reproductibilité par qui ? soi-même? un collègue? un concurrent? un reviewer? une instance de vérification?  
* Reproductibilité pour quoi : pour valider ? pour contredire ? pour interpréter ?  
* Reproductibilité comment ? avec la même instrumentation ? le même protocole ? la même conclusion par d'autres moyens ?  
* De fait, qu'est-ce qui est "pareil" ? de strictes mesures ? des patterns concordants de résultats ? des conclusions généralisatrices ?  
* Et enfin, quand a-t-on besoin d'être "pareil" ? pour vérifier ? pour démontrer ? pour infirmer ou contredire ? pour généraliser ?    
Par ailleurs, la "reproduction" doit elle être hypothétique ou effective ? Il est notoire que les scientifiques n'ont (en général) aucune motivation à reproduire les expériences des autres : Puisque la récompense de l'activité de recherche est la publication et que la valeur de la publication réside dans l'originalité, la question reste souvent hypothétique, et les rares cas de tentatives de reproduction se font lors de controverses.

*Est ce que les deux études de nature sont de la reproductibilité ou pas?*  

Paradoxalement, malgré le flou qui l'entoure et la faible activité de reproduction en pratique, la reproductibilité est souvent citée comme "la moindre des choses" dans les bonnes pratiques scientifiques, voire un "gold standard" de la science. Elle est par exemple prégnante dans la critique de l'activité de publication et en particulier du protocole de peer reviewing. La nécessité de la reproductibilité est ainsi souvent brandie comme un principe moral indiscutable, et les conditions de la réalisation de ce principe sont souvent hypothétiques. La critique de l'activité de reviewing, par exemple, existe de plus en plus et des propositions sont envisagées (Ross-Hellauer, 2017), mais cette remise en cause, parfois appliquée dans des revues scientifiques d'avant garde, se heurte à l'immobilisme des revues les plus prestigieuses, celles qui pèsent le plus.

*Raoul ? Sur critique du peer reviewing*

* Vertus épistémiques : le venin de vipères
* Reproduire des expériences en histoire des sciences : Joule et les brasseries

* Cette reproduction dépendait de trop de savoirs tacites. Le but de cette "technique littéraire" (litterary technology) n'était effectivement pas (et n'est toujours pas dans les publications aujourd'hui) exactement la reproductibilité, mais plutôt la légitimité.

### Chapitre 2: plusieurs types de reproductibilités  

* Computationelle  
* Expérimentale directe: Essais standardisé en médecine clinique  
* Expé indirecte: Semis standardisé (psychosociale, neurosciences...)  
* Repro par expértise (archéologie)   
* Observatino reproductibles (radiologie, sociologie)  
* Recherche non repro: Anthropologie (n'as pas de sens ici). ils se concentrent sur les pricessus de production des données.   
<br>
La conclusion de Leonelli à propos de cette typologie en six catégories est que l'exigence de reproductibilité (en tant que moyen d'obtenir la fiabilité) pose problème, et ce encore plus si elle est définie dans un sens étroit, basé sur des préceptes qui n'ont de sens que dans un seul domaine scientifique.

### Chapitre 3  
* Ref to check *
* Crise médiatique
* En Psycho: En 2011, est créé le Reproducibility Project, puis en 2013, le Center for Open Science, opération de reproduction d'expériences en psychologie impliquant toute une communauté scientifique. ([Chambers 2017](https://press.princeton.edu/books/hardcover/9780691158907/the-seven-deadly-sins-of-psychology))
* Essais cliniques: Au début des années 2000, la contestation a porté sur les biais liés au financement privé des recherches, avec en point d'orgue le livre "The Truth About the Drug Companies: How They Deceive Us and What to Do" (Angell, 2004) provenant de la communauté académique médicale. La mise en évidence récente, lors d'études financées par le privé, que les problèmes de reproductibilité existent autant dans la recherche publique que dans la recherche privée suggère que ce manque de reproductibilité est lié à autre chose que l'influence d'intérêts financiers. Nelson le voit donc comme une sorte de contre-attaque de l'industrie pharmaceutique pour sortir du rôle de méchant dans lequel elle est cantonnée
* Meta sciences (statistics): Les problèmes épistémiques de reproductibilité sont pourtant bien plus divers que cette seule question, mais la reproductibilité statistique est de loin la plus médiatique. See "Why Most Published Research Findings Are False" (au titre particulièrement nuancé) est de loin la plus citée ([Ioannidis, 2005](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124)).

### Chp 4: Reprod computationelle

Check [Disunity of sciences, 1996](https://www.sup.org/books/title/?id=2121) & [Norton 2010](https://www.journals.uchicago.edu/doi/abs/10.1086/656542).     

- La repro comme gold standard a ateindre   
- Pourtant, même s'ils sont interpénétrés, le statistique et le computationnel ne posent pas les mêmes problèmes de reproductibilité.(souvent confondus !!!) 

De fait, une grosse partie de l'activité computationnelle est réalisée par des scientifiques dont ce n'est pas le métier : ni dans le coding, ni dans le management, ni dans la diffusion et le licensing. La définition et l'organisation de bonnes pratiques sont des préoccupations des chercheurs [Bénureau et Rougier, 2018](https://www.frontiersin.org/articles/10.3389/fninf.2017.00069/full) [Stodden, 2016](https://onlinelibrary.wiley.com/doi/10.1002/9781118865064.ch9)

* On peut de manière similaire décrire deux visions différentes de fiabilité scientifique computationnelle. L'un considére le software comme "user-oriented". Dans ce cas, le programme est vu comme un outil dont on peut soulever le capot et vérifier comment il marche : la transparence est la vertu épistémique garantissant la reproductibilité, contrairement à une "boîte noire". L'autre considère le software comme "market-oriented", il est produit industriellement et la confiance est basée sur la robustesse d'un produit industriel imposant une forme de standard, même si propriétaire. Dans ce cas, la reproductibilité est basée sur l'assurance de la fiabilité par l'imposition d'une norme industrielle (Hocquet et Wieber, 2020).

## Seconde partie: transparence
Au moins trois types de transparence:  
* data transparency : "Providing full access to data itself"  
* analytic transparency : "Information about data analysis"  
*production transparency : "Process of data collection"  


But de pre-registration (Nosek et al. 2017) peut également participer à une recherche plus reproductible. L'une de ses finalités est de prévenir les risques de HARKing - Hypothesizing After the Results are Known.

**Le terme "transparence" renvoie donc plutôt au fait de rendre accessibles à son lectorat les éléments sur lesquels s'est construit le raisonnement**: : sources citées, données analysées ou description des données, corpus, etc. La notion de traçabilité occupe donc une place centrale. L'accent n'est pas mis sur le fait d'aboutir aux mêmes conclusions.  
la démultiplication des données disponibles (corpus numérisés, catalogues de références, sources en texte intégral, données obtenues grâce à des logiciels, etc.) et leur fragilité (obsolescence des supports, des formats et des logiciels) constituent autant d'atteintes potentielles à la traçabilité de la recherche.  

*Le codebook*, un exemple d'outil pour les méthodes qualitatives



# Entretien avec François Briatte: 
Ses recherches ont porté sur les politiques de santé publique en Europe, la sociologie des mouvements sociaux, la sociologie de la quantification, et l’analyse de réseaux appliquée à la collaboration législative ([son site])(https://f.briatte.org/)

* Graphviz un outils ôpur représenter son workflow
* [Cascad](https://www.cascad.tech/), un outil de certification de la reproductibilité. Utile surtout quand les données sont confidentielles !!
* Exemple de problème: C’est donc parfois l’horreur absolue lorsqu’un referee demande à refaire une estimation et que le chercheur ne retrouve pas le même résultat et n’est pas complètement sûr des programmes utilisés ! Il faut dire aussi, que les estimations économétriques reposent souvent sur la maximisation d’une vraisemblance, une fonction souvent complexe à maximiser et il arrive qu’un changement de version de logiciel (Stata par exemple, mais une mise à jour d’un package R ou un package R obsolète peuvent aussi réserver de belles surprises) vienne perturber la délicate mécanique mise au point (*Genre de problème déjà vécu*) Comment résoudre ce problème a part avec docker ?  
* un article reflète mal le processus de recherche en amont de sa publication.




