# Infrastructure Starfleet

Projet de mise en place d'une infrastructure serveur sous Debian.

## Objectif

L'objectif de ce projet est de mettre en place une infrastructure composée
d'un serveur Debian et d'une machine cliente permettant de tester les
différents services proposés par le serveur.

## Architecture

L'infrastructure est composée de :

- 1 VM serveur Debian sans interface graphique
- 1 VM cliente Debian avec interface graphique

Le serveur fournit notamment :

- DHCP
- DNS
- Nginx
- PHP 7
- PHP 8
- MariaDB
- phpMyAdmin
- FTP sécurisé
- LDAP
- HTTPS
- administration

## Domaine

Le domaine interne utilisé est :

"starfleet.lan"
