# JSON service for webapps

Pour faciliter le prototypage d'applications, notamment d'applications clientes riches dans le navigateur, il serait intéressant de mettre en oeuvre un service simplifiant le stockage des données.

Ce service s'apparenterait à une architecture sans serveur ([Serverless architecture](http://martinfowler.com/articles/serverless.html)) mais dont on garderait surtout la simplicité de mise en oeuvre.

## Fonctionnalités

Deux fonctionnalités principales :

- accès simple via API HTTP
- gestion minimale des droits : il s'agit surtout de pouvoir isoler des collections de données entre applications

La solution d'encodage préférentielle est JSON, parce-que webapps JavaScript et besoin de schéma flexible.

## Solutions

### File system + REST

...

### Base document

MongoDB ?

### API serveless

[Horizon + RethinkDB](http://horizon.io/)
