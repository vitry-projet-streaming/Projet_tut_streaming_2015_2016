# Projet Tuteuré IUT Vitry 2015/2016
## Solution de Streaming


### Auteurs

  Bastien Sauvan : sauvan.b@gmail.com
  Paul Cocu : paul.cocu1@gmail.com 
  François Le Nalio : francois.le.nalio@gmail.com 


### Objectif 

Proposer un service de Streaming  de retransmission de l'Euro 2016 en temps réel.

### Contenu du Github

Vous trouverez dans chaque dossier, la configuration de tous nos serveurs.

Vous pouvez également trouver notre rapport de projet au format PDF ou au format brut en LaTeX 


### Etapes clés

Coté Serveurs :

Récupération du flux
Ouverture du flux → Convertir le flux → Optimiser → Envoyer sur Server1
Duplication du flux de Serveur 1 → Serveur 2
Rendre le flux disponible sur les deux serveurs


Coté Client

Plate-forme Web avec Lecteur Flash pour l’utilisateur
Requête vers le Load Balancer
LoadBalancing → Algorithme de LB → redirige la requête vers Serveur Streaming
Serveur Streaming envoi le flux aux clients

