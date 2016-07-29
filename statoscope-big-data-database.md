# Big Data et base de données

C'est connu : les Big Data ont provoqué du point de vue technique des changements profonds dans la manière de stocker la donnée.

Le point de départ, c'est la constatation que les systèmes relationnels de base de données, qui ont dominé le monde informatique depuis les années 70, ne sont pas adaptés à ce nouveau monde, même si, nous le verrons, nombre de concepts reste d'actualité.

Souvent, cette transformation est résumée par le concept "base de données **NoSQL**". Ce terme, ni très juste ni très bien défini, signifie surtout la rupture mentionnée plus haut avec le modèle relationnel. Ces contraintes sont théorisées à travers le théorème CAP, Consistency / Availability / Partition tolerance : trois propriétés fondamentales des base de données qui, selon ce théorème, ne sont possible que deux par deux.

Les systèmes relationnels sont CA, c'est-à-dire qu'ils garantissent une cohérence dans les données et leur disponibilité. Les base NoSQL sont, elles, AP, hautement disponibles et permettent de distribuer les données [ref. article sur distribution].

Cette vision est bien sûr très haut niveau, et ne dit rien du modèle de données sous-jacent et de l'impact sur l'utilisation de telles bases de données.

Les bases NoSQL offrent des modèles de données très divers, du document au format flexible au graphe reliant des entités entre elles en passant par des spécialisation comme les bases de séries temporelles. Examinons de plus près certaines solutions phares : Cassandra, MongoDB et Neo4J.