# GTFS
Ce répertoire contient les données GTFS officielles de [Transcollines](https://www.transcollines.ca/)!
Pour plus d'information sur le format GTFS, consultez [la spécification officielle](https://github.com/google/transit/blob/master/gtfs/spec/en/README.md).

**Assurez-vous de lire les conditions d'utilisation (situées dans le fichier LICENCE.md) avant de commencer à utiliser les données de Transcollines.**

> Dernière mise à jour des conditions d'utilisation: 3 mars 2023

## Fares-V2 (Tarifs)
En date du 17 juin 2022, les développeurs ont maintenant accès aux informations sur la tarification selon la nouvelle norme GTFS _Fares V2_ dans le fichier GTFS secondaire _transcollines-qc-ca-fares.zip_. Lorsque la norme _Fares-V2_ sera adoptée plus globalement, les fichiers de tarification seront ajoutés au GTFS "Régulier" et le fichier spécial _fares-V2_ cessera d'être produit. Notez également qu'en raison de particularités en ce qui a trait aux correspondances vers le réseau de la STO, certains noms de titre sont particulièrement longs.
## Transcollines à la demande
Transcollines travaille présentement avec son fournisseur logiciel pour le transport à la demande afin de pouvoir fournir aux développeurs un fichier GTFS-Flex contenant les informations sur ce service. Nous vous encourageons à vous inscrire à la liste de distribution des développeurs afin d'être avisé dès que ces données seront disponibles.
## Télécharger le GTFS:
Pour télécharger le GTFS de Transcollines, utilisez le lien ci-dessous.
https://github.com/transcollines/gtfs/raw/master/transcollines-qc-ca.zip
**En téléchargeant le GTFS, vous acceptez les conditions d'utilisation détaillées dans le fichier `licence.md`**
## GTFS-Realtime
Transcollines fournit également les informations en temps réel, dans le format GTFS-Realtime. 
Pour plus de détails, rendez-vous au [github.com/transcollines/gtfs-rt](https://github.com/transcollines/gtfs-rt)
## Inscription à la liste de distribution des développeurs Transcollines
Transcollines utilise cette liste de distribution pour informer les développeurs de changements importants au fil GTFS de Transcollines. Il est fortement encouragé de s'y inscrire. Vous devriez recevoir environ un courriel aux deux ou trois mois.
[Inscrivez-vous ici.](https://forms.office.com/Pages/ResponsePage.aspx?id=E7Fe_cNXKEamfise0d6K-7z88p3eAzZIns4uRERv9ZRUNFRTMVM0OFo1NjhMR0ZINEhFUDdVQzU2Uy4u)
## Extensions particulières aux fichiers GTFS de Transcollines
* **`trips.trip_direction_headsign`**: Ce champ est utilisé pour indiquer la direction du voyage qui est présentée aux utilisateurs sur les afficheurs de destination des autobus en alternance avec le contenu du champ `trips.trip_headsign`
* **`trips.exceptional`**: Veuillez Consulter [ceci](https://developers.google.com/transit/gtfs/reference/gtfs-extensions#trips.txt).

## Registre des applications
Vous avez créé un outil utilisant les données ouvertes de Transcollines? Nous avons l'intention d'éventuellement créer une galerie d'applications sur notre site web et aimerions y présenter votre application! Informez-nous de votre application [ici!](https://forms.office.com/Pages/ResponsePage.aspx?id=E7Fe_cNXKEamfise0d6K-7z88p3eAzZIns4uRERv9ZRUMVk0Wko5VEhINlBNSjY1TkUwU0Y2N1FIQy4u)

### Transcollines vous remercie pour votre contribution à la mobilité dans l'Outaouais Rural!
