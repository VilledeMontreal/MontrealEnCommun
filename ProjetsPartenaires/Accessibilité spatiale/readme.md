
## Villes des courtes distances : <br/> Développement d’indicateurs d’accessibilité aux destinations à la marche et à vélo

Polytechnique Montréal, l’Université McGill et l’Institut national de la recherche scientifique (INRS) mènent une étude visant à générer des indicateurs d’accessibilité aux destinations à la marche et à vélo sur le territoire de la Ville de Montréal. 

Ce projet, financé par Mitacs et la Ville de Montréal, est encore en phase de développement. 
Les résultats préliminaires peuvent être visualisés sur la plateforme Curbcut : https://susmtl.ca/?geo=CMA&tb=city_amenities&lng=fr
<br/>

#### Mais l’accessibilité, c’est quoi exactement et pourquoi est-ce important?

Dans un contexte de planification urbaine, l’accessibilité fait référence à la facilité avec laquelle les individus peuvent accéder aux opportunités urbaines dispersées sur le territoire.

Une grande accessibilité en transports actifs est souvent synonyme de bonne qualité de vie et d'équité sociale. Des destinations accessibles à la marche et à vélo encouragent également les déplacements actifs et ainsi, mènent à la réduction des émissions de gaz à effet de serre et des coûts associés au transport et à l’amélioration de la santé de la population.

Ainsi, les indicateurs d'accessibilité aux destinations supportent la planification intégrée des transports et de l’aménagement du territoire dans une optique de mobilité durable.

#### Objectifs
##### Objectif général
Favoriser l’adoption d’approches axées sur l’accessibilité aux destinations dans la planification des transports et de l’aménagement du territoire.

##### Sous-objectifs 
1.	Développement d’indicateurs d’accessibilité aux destinations à la marche et à vélo ;
2.	Conception d’un outil interactif et paramétrable de visualisation ;
3.	Adoption des indicateurs par les acteurs locaux.


#### Méthodologie 
Les indicateurs de ce module représentent le nombre de destinations accessibles à la marche et à vélo à partir d'une origine spécifiée à l'intérieur d'un seuil de temps donnée (méthode d’opportunités cumulatives).

Chaque indicateur est calculé au niveau des îlots de diffusion, soit les plus petites unités spatiales définies par Statistique Canada.

##### Zone d’étude 
- Territoire de la Ville de Montréal (villes liées exclues) 

##### Seuils de temps (*homogènes pour tout le territoire et toute la population*)
- Marche : 15 minutes / 900 m
- Vélo : 20 minutes / 4 km

##### Source de données
- Données ouvertes de la Ville de Montréal
- DMTI
- Réseau de rues Open Street Map (OSM) 

##### Calculs
- Les caractéristiques et la qualité des destinations ne sont pas prises en compte.
- Les temps de déplacement sont calculés avec l'outil [r5r](https://cran.r-project.org/web/packages/r5r/vignettes/intro_to_r5r.html) (« itinéraires rapides et réalistes ») dans R. Les calculs prennent en considération les infrastructures piétonnes et cyclistes ainsi que l'élévation, mais pas les coûts de virage et de traversée d’une intersection. 


#### Résultats
Visualisation des indicateurs en ligne sur l'onglet Transport > Ville de courtes distances de la plateforme Curbcut : https://susmtl.ca/?geo=CMA&tb=city_amenities&lng=fr

