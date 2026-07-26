# GTFS

Ce répertoire contient les données GTFS officielles de [Transcollines](https://www.transcollines.ca/)!
Pour plus d'information sur le format GTFS, consultez [la spécification officielle](https://github.com/google/transit/blob/master/gtfs/spec/en/README.md).

**Assurez-vous de lire les conditions d'utilisation (situées dans le fichier LICENCE.md) avant de commencer à utiliser les données de Transcollines.**

> Dernière mise à jour des conditions d'utilisation: 26 juillet 2026.

## Fares-V2 (Tarifs)

En date du 17 juin 2022, les développeurs ont maintenant accès aux informations sur la tarification selon la nouvelle norme GTFS _Fares V2_ dans le fichier GTFS secondaire _transcollines-qc-ca-fares.zip_. Lorsque la norme _Fares-V2_ sera adoptée plus globalement, les fichiers de tarification seront ajoutés au GTFS "Régulier" et le fichier spécial _fares-V2_ cessera d'être produit. Notez également qu'en raison de particularités en ce qui a trait aux correspondances vers le réseau de la STO, certains noms de titre sont particulièrement longs.

## Transcollines à la demande

Transcollines travaille présentement avec son fournisseur logiciel pour le transport à la demande afin de pouvoir fournir aux développeurs un fichier GTFS-Flex contenant les informations sur ce service. Nous vous encourageons à vous inscrire à la liste de distribution des développeurs afin d'être avisé dès que ces données seront disponibles.

## Télécharger le GTFS:

Pour télécharger le GTFS de Transcollines, utilisez le lien ci-dessous.
https://github.com/transcollines/gtfs/raw/master/transcollines-qc-ca.zip
**En téléchargeant le GTFS, vous acceptez les conditions d'utilisation détaillées dans le fichier `licence.md`**

## Extensions particulières aux fichiers GTFS de Transcollines

- **`trips.trip_direction_headsign`**: Ce champ est utilisé pour indiquer la direction du voyage qui est présentée aux utilisateurs sur les afficheurs de destination des autobus en alternance avec le contenu du champ `trips.trip_headsign`

## Fichiers GeoJSON pour les systèmes d'information géographique (SIG)

Les utilisateurs de SIG et de tout autre programme de cartographie peuvent utiliser les fichiers `parcours.geojson` et `arrets.geojson` qui se situent dans le dossier `GEOJSON`. Ces fichiers sont générés à partir des données GTFS. Leur utilisation est soumise aux mêmes conditions d'utilisation que l'utilisation des fichiers GTFS, présentées dans le fichier `license.md`.

### Transcollines vous remercie pour votre contribution à la mobilité dans l'Outaouais Rural!
