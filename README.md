# Juste-prix

J'ai créé un contrat complet pour un jeu du Juste Prix ! Voici ses fonctionnalités :
🎮 Fonctionnalités principales :
Pour l'organisateur :

demarrerPartie(uint256 _prixSecret) : Lance une nouvelle partie avec un prix secret (0-1000$)
annulerPartie() : Annule la partie en cours si nécessaire
transfererOrganisation() : Transfère les droits d'organisateur

Pour les joueurs :

proposer(uint256 _proposition) : Propose un prix

Retourne "C'est plus !" si trop bas
Retourne "C'est moins !" si trop haut
Retourne "Gagné !" si exact



Consultation :

obtenirStatistiques(address) : Voir les victoires et tentatives d'un joueur
obtenirTentative(uint256) : Consulter l'historique des propositions
partieActive() : Vérifier si une partie est en cours

📊 Caractéristiques :
✅ Pas de fonds - Jeu purement ludique
✅ Historique complet - Toutes les tentatives sont enregistrées
✅ Statistiques - Suivi des performances de chaque joueur
✅ Événements - Pour suivre l'activité en temps réel
✅ Sécurisé - Modificateurs pour contrôler l'accès
Le jeu est prêt à être déployé et utilisé pour des compétitions amicales sur la blockchain !RetryClaude can make mistakes. Please double-check responses. Sonnet 4.5
