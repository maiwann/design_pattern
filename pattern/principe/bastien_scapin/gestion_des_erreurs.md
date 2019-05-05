---

type : principe

---

#  Gestion des Erreurs

Puisqu'il est dans la nature de l'être humain de se tromper, on doit prévoir que l'utilisateur fera des erreurs. On doit surtout concevoir des moyens de pallier ce problème :
- protéger l'utilisateur contre d'éventuelles erreurs
- l'avertir lorsqu'il a commis une erreur que l'on peut détecter
- corriger ou l'aider à corriger ses erreurs :

## Protection contre les Erreurs

le système doit avoir été conçu pour détecter et prévenir les erreurs d’entrées de données ou de commandes ou les actions aux conséquences néfastes. On peut prévenir des erreurs minimes (exemple la saisie d'une lettre dans un champ de numéro de téléphone) ou plus importantes (exemple la suppression d'un document).

> Lorsque l'utilisateur est sur le point d'accomplir une action irréversible, le système doit demander confirmation. Dans ce cas, le choix par défaut devrait être celui qui annule l'action demandée. On évite ainsi que l'utilisateur détruise des données par mégarde.
Cette recommandation entre toutefois en conflit avec les standards utilisés dans certains systèmes d'exploitation et applications. Il s'agit donc de choisir en fonction du contexte le choix par défaut proposé par le système.

## Qualité des Messages d'Erreurs

Messages contextuels, informer l'utilisateur sur la raison de l'erreur, sur sa nature et sur les façons de la corriger si elles existent, dans un langage accessible (non technique)

## Correction des erreurs

Faciliter la tâche de correction, guider l'utilisateur concernant les étapes à suivre afin de rectifier l'erreur.

> Un pré requis à cette possibilité est l'identification précise de l'erreur. Si le système a clairement identifié l'erreur, il devrait pouvoir la mettre en valeur et proposer de modifier précisément ce qui est erroné.

# Cartes liées

+!BastienScapin
