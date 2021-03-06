# Projet Réservation de gîtes
Projet par groupes - Temps estimé : 15 jours
Technologies, outils et concepts travaillés : PHP, programmation orientée objet (POO), HTML, CSS, MCD

## Description du projet :
Vous allez réaliser une plateforme de réservation de gîtes se situant dans une zone géographique précise (au choix). La plateforme est gérée par un **seul administrateur** qui pourra s'occuper d'**ajouter, modifier ou supprimer des gîtes**.

**Côté client pas besoin de compte utilisateur**. On pourra visualiser la liste des différents gîtes ainsi que leurs détails. On pourra aussi effectuer une recherche pour trouver un gîte selon ses critères et ses disponibilités.

Il vous faudra créer une `classe` représentant un hébergement. Il existera plusieurs catégories d’hébergements (exemple : chambre, appartement, maison, villa…), pour chacune il faudra créer une instance de cette `classe`. Il faudra au minimum pour chaque hébergement :

1. Intitulé de l’hébergement
2. Description
3. Photo(s)
4. Nombre de couchages
5. Nombre de salles de bain
6. Emplacement géographique
7. Prix 
8. Disponibilité
9. Chaque catégorie d’hébergement peut avoir des spécificités, par exemple pour un appartement ou plus grand on peut indiquer  le nombre de pièces, pour une maison la présence d’un jardin particulier etc.



### Côté administrateur on aura :

__Un back-office (connecté à une base de données) permettant__ : :chart_with_downwards_trend:

- [ ] De visualiser l'ensemble des gîtes et leur statut (occupé ou libre)
- [ ] D’ajouter des gîtes
- [ ] De supprimer des gîtes
- [ ] De les modifier


### Côté utilisateur on aura :

Une page accueil avec :
- [ ] La liste des gîtes disponibles
- [ ] Un formulaire de recherche (date de départ, date de fin, nombre de couchages
- [ ] Une fiche par gîte avec un formulaire de réservation
- [ ] La réception d'un mail lorsque la réservation est effectuée


__Gestion des disponibilités__ :

Lorsqu'un gîte est réservé pour une période il devient indisponible pour celle-ci. Il reste accessible par une recherche mais il faudra indiquer les jours d'indisponibilité. Il est possible de faire une réservation pour les jours disponibles.

 

  Les plus : à réaliser si vous avez le temps

    Afficher un calendrier de disponibilité de chaque gîte :date:
    Afficher la localisation des gîtes sur une carte
 

**Rappel des tâches** :
 
 - [ ] Benchmark + maquette du site (temps estimé : 3 jours)
 - [ ] Concevoir un MCD
 - [ ] Concevoir un MLD
 - [ ] Concevoir le modèle physique
 - [ ] Concevoir le diagramme de la classe "hébergement" ensemble
 - [ ] Se répartir pour la réalisation du back-end & front-end
 - [ ] Faire un point tout le long du projet pour valider chaque étape.


 

Objectifs :
  Découvrir et manipuler la programmation orientée objet en PHP
  Consolider les bases du CRUD
  Consolider/approfondir les bases du langage SQL
Thèmes : 
  Programmation orientée objet
  Bases de données

Ressources :
Parcours "PHP > Programmation orientée objet" sur vos-formations.com

[Intro POO Pierre Giraud](https://www.pierre-giraud.com/php-mysql-apprendre-coder-cours/introduction-programmation-orientee-objet/)

[Grafikart](https://www.grafikart.fr/formations/programmation-objet-php)


[SQL](https://sql.sh/)

