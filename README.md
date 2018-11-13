## Project Name: 

application de conversion de documents sous le cloud (SAAS).

## Prerequisites :

vous avez besoin d'un browser et la connection a l'internet pour lancé ce programme.

## Application Architecture :

cette application est basé sur une collection de web services pour les conversions , permet de mettre les données à la
disposition d'utilisateurs qui n'ont pas forcément un accès direct aux données , rendez l'application accessible via une 
multitude d'applications exécutées sur des ordinateurs de bureau, des tablettes PC et des smartphones. 
l'ensemble des services : 
  - service web de conversion il s'agis de converter le document.
  - service web euthentication il s'agis de validé le client .
  - service web send-email il s'agis denvoyer email vers le client .
  - service web download il s'agis de telecharger le document et le supprimé apres 5 min.  

## Installing :

tant que nous somme dans le cloud et cette application est comme 'SAAS' donc ona pas besoin d'installé aucun chose 
on a besion seulment le browser pour uploder le document et afficher le resultat.

## Files Includes With This Project :
source code pas encore 
   ### base de données :
     	|-------------------------|         |-------------------|
            |          client         |         |   administrateur  |
            |-------------------------|         |-------------------|
		| id                      |         | id                |  
		| name                    |         | name              |
		| email                   |         | email             |
		| conversion_nbr          |         |                   |
		|-------------------------|         |-------------------|

## Running The Application :

ouvrir le browser , tapez ce URL ( pas encore ) ,  uploder le document et voila  le resultat. 

## Deployment :

pour deploy cette application créer compte sur le GITHUB , créer  compte sur openshift 
ajouter les classes dans le repository dans le compte de GITHUB 
pendant la preparation des programmes d'environment de programation dans openshift ajouter le lien
du compte de repository de GITHUB pour importer les classes pour les exécutées , ajouter la base de données  

## Built With :

Spring boot 
Oracle database
Openshift platform 

## Authors :

Bouchelouche Mohamed 
Safi Oussama
Touahri Ilyes

## License :

Ce projet est sous licence MIT d'université de constantine

## Acknowledgments :

Remerciements à l'enseignante de module, 
Remerciements à l'enseignant de TP 
