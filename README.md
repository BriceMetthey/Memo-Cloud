# Memo-Kubernetes

## Références documentaires

[Outil de diagramme : draw.io](http://draw.io)

[Documentation microk8s](https://microk8s.io/docs) 

[Documentation dashboard microk8s](https://microk8s.io/docs/addon-dashboard)

[Video sur l'essentiel](https://www.youtube.com/watch?v=NChhdOZV4sY)

## Description

Kubernetes : L'orchestrateur le plus populaire pour la gestion des conteneurs.
Le conteneur n'a pas conscience de ce qui se passe en dehors de la machine hôte.
Gérer les différents conteneurs sur ces différents hôtes linux qu'ils soient physiques ou virtuels.

## Principes

### Kubernetes permet de : 

* Créer des services applicatifs sur plusieurs conteneurs

* Planifier leur execution sur plusieurs conteneurs

* Garantir leur intégrité

* Assurer le monitoring


### Les composants majeurs de l'architecture de Kubernetes

Il y a le **Kubernetes Master** qui est le serveur controlant les nodes

## Start / Stop cluster

`microk8s start`

`microk8s stop`
