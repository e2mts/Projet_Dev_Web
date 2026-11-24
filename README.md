# Projet_Dev_Web
Projet scolaire de développement web, thème choisi : location de matériel.

GROUPE X :
Eleana Baptista
Adam Bruneau
Elisa Seillier

Objectif du projet

Créer une application permettant de gérer du matériel, des réservations et des suivis d’usage.
Les utilisateurs de matériel.
Les administrateurs catalogue et les opérations.

Technique et générale

API
- doit suivre une logique RESTful claire et cohérente.
- minimum trois entités ( hors User et tables de relations )

Sécurité 
- deux rôles minimum ( User et Admin ou équivalent )
- les droits doivent être réellement appliquées
    Un utilisateur n’accède qu’à ses propres données ou aux éléments publics et un administrateur possède des actions supplémentaires.

Pas de fuite de données, et pas de possibilité de modifier des donées qui ne nous appartiennent pas.

Front ( React )
- minimum en composant générique, réutilisable ( composant de tableaux, gestion de liste, form builder, modale de confirmation, pagination ou recherche )
- interface adaptée selon le rôle (certaines actions réservées aux administrateurs)
