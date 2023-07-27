# Segmentations-des-clients-similaires-des-fins-de-marketing
Grande Dimension

### Introduction
L’analyse en grande dimension correspond à l’analyse de de données qui comportent un nombre de variables important par rapport au nombre d’observations. Lorsqu’on se trouve dans ce cadre la, les modèles "classiques" d’analyse échouent systématiquement car ils sont dépassés et pas adaptés. C’est notamment le cas avec nos données. En effet, la base de données continent les informations sur le comportement de près de 9 000 détenteurs actifs de cartes de crédit au cours des 6 derniers mois, au niveau individuel, et contient également 18 variables décrivant leur comportement. Notre objectif est donc de diviser le marché en groupes ayant des comportements similaires à des fins marketing comme par exemple la personnalisation d’offre, ou plus globalement la mise en place de stratégies plus efficaces.
Il était donc question dans ce projet de mettre en oeuvre certaines stratégies que nous avons
vu en cours d’analyse en grande dimension afin d’opérer une segmentation de la clientèle.
Afin d’évaluer la performance de chacun de nos algorithmes, nous avons choisi d’associer comme métriques :
— Silhouette score : c’est une métrique qui prend un point, mesure la moyenne des distances entre ce point et ceux de son cluster, puis compare avec la moyenne des distances entre ce point et ceux des autres clusters. Il est compris entre -1 et 1, 1 étant le cluster
optimal et -1 le plus mauvais cluster.
— Calinski score : il compare la variance intra-cluster et la variance inter-cluster. Lorsque ce score est élevé, cela veut dire que les clusters sont bien définis et distincts.

