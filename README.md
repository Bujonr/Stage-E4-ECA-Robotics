# Stage ECA Robotics

**Contexte**

**Eca Robotics**, en tant qu’unique constructeur des quatre types de drones à savoir aériens, terrestres, de surfaces et sous-marins, se doit **d’exploiter efficacement toutes les données de logs** produites par ses différents véhicules. En fonction du type de véhicule, la typologie peut changer sensiblement. Les résultats escomptés d’une telle exploitation sont divers ; améliorer la précision de nos indicateurs, mieux configurer les véhicules, débriefer les missions plus rapidement, comprendre les erreurs remontées ou encore plus globalement mettre en place des algorithmes de maintenance prédictive. Dans le cadre du **contexte sanitaire exceptionnel dû au COVID-19**, Eca Robotics m'a proposé un **stage en télétravail** avec possibilité de revenir sur site si le contexte le permet. La possibilité **d’utiliser des données internes en télétravail**, sur mon ordinateur personnel, est donc **exclue**. Des **données en open source seront donc utilisées**. On peut dans notre cas exploiter les données publiques AIS qui sont proches des problématiques d'ECA Robotics.
#
 
**L'objectif du stage :**

L'objectif principal du stage est de réaliser un **benshmark** entre plusieurs solutions permettant **l'analyse de base de données de séries temporelle et géo-temporelle**. 

Pour cela, il sera donc nécessaire **d'ingérer des données publiques dans les bases de données sélectionnées**. En ce qui concerne **l'analyse de donnée**, il faudra réaliser **une exploitation graphique via des cartes des données spatio-temporelles**.

Les solutions étudiées sont les suivantes : 

- **TimescaleDB** 
- **InfluxDB**
- **Warp10**

Pour ce qui est de l'outil permettant une exploitation graphique :

- **Grafana**
