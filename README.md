E-Cars est une simple application cmd de location des voitures écrite en langage C.

Struct Voiture: est une structure pour représenter une voiture qui contient la marque, le modele et la disponibilité de la voiture avec un pointeur qui pointe sur la prochaine voiture.

Struct Location: est une structure pour représenter une location qui contient la date et le prix de la location ainsi des pointeurs qui pointent vers la voiture louée et vers la prochaine location.

Pointeurs vers les listes de voitures et de locations.

afficherVoituresDisponibles() est une fonction pour afficher les voitures disponibles.

afficherHistoriqueLocations() est une fonction pour afficher l'historique des locations.

louerVoiture(char* marque, char* modele, char* date) est une fonction comportant la marque, le modele de la voiture et la date de location comme paramétres permettant de louer une voiture.

Stockage des informations concernant cette foncion dans un fichier appelé "locations.txt".

afficherDescriptionVoiture(char* marque, char* modele) est une fonction comportant la marque et le modele de la voiture comme paramétres permettant d'afficher la description d'une voiture.

supprimerVoiture(char* marque,char* modele) est une fonction comportant la marque et le modele de la voiture comme paramétres permettant de supprimer une voiture.

modifierDescriptionEtatVoiture(char* marque,char* modele,char* nouvelleMarque,char* nouveauModele,int nouvelleDisponibilite) est une fonction pour modifier la description et l'état d'une voiture.

rechercherVoiture(char* marque, char* modele) est une fonction comportant la marque, le modele de la voiture permettant de rechercher une voiture.

struct Reservation: est une structure qui contient la date de la reservation et des pointeurs qiu pointent vers la voiture réservée et vers la prochaine réservée pour représenter une réservation.

Pointeur vers la liste des réservations.

reserverVoiture(char* marque,char* modele,char* date) est une fonction comportant la marque, le modele de la voiture et la date de la resevation permettant de réserver une voiture.

Stockage des informations concernant cette foncion dans un fichier appelé "reservations.txt".

genererRapportLocation(struct Location* locations) est une fonction pour générer un rapport de location pour l'agence.

Stockage des informations concernant cette foncion dans un fichier appelé "rapport.txt".

calculerRevenuTotal() est une fonction pour calculer le revenu total de cette agence.

afficherRevenuTotal() est une fonction pour afficher le revenu total.

Enfin la fonction principale en faisant l appel a tous les fonctions ci-dessus.

Stockage des informations concernant cette foncion dans un fichier appelé "Main.txt".
