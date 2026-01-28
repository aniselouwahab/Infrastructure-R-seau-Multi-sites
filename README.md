
# Infrastructure Réseau Multi-sites : Nice ↔ Abidjan

## 1. Description du Projet

Ce projet simule l'interconnexion réseau entre deux sites géographiques distants (Nice et Abidjan) via Cisco Packet Tracer. L'objectif est de mettre en place une architecture robuste, sécurisée et redondante, permettant une communication fluide entre les deux infrastructures comme s'il s'agissait d'un réseau local unique.

## 2. Topologie

Site Abidjan : Réseau local avec segmentation VLAN et serveurs de ressources.

Site Nice : Réseau local avec services Web et DNS.

![image alt](https://github.com/aniselouwahab/Infrastructure-R-seau-Multi-sites/blob/f0d4fe8bce4b7969b302c4050da4d44844da8a89/Capture%20d'%C3%A9cran%202026-01-28%20154907.png)

## 3. Fonctionnalités implémentées

- Segmentation Réseau : Configuration de VLANs pour isoler les flux (Administration, Employés, Serveurs).

- Routage Inter-VLAN : Mis en place sur des commutateurs de niveau 3 (Multilayer Switches).

- Haute Disponibilité : Configuration de l'EtherChannel pour l'agrégation de liens, augmentant la bande passante et assurant la redondance.

- Connectivité Distante : Mise en œuvre de routes statiques entre les routeurs de bordure pour le lien inter-sites.

- Services Réseau : Déploiement de serveurs simulés (DHCP, DNS, Web).

- Sécurité : Architecture conçue pour l'intégration future d'un VPN Site-à-Site.


## Technologies utilisées

- Outil de simulation : Cisco Packet Tracer

- Matériels : Routeurs 2811, Switches 2960, Switches Multicouches 3650.

- Protocoles : 802.1Q (Trunking), LACP (EtherChannel), Routage Statique, IPv4.



## 5. Installation et Test

- Téléchargez et installez Cisco Packet Tracer (version 8.0 ou supérieure).

- Clonez ce dépôt : git clone https://github.com/aniselouwahab/Infrastructure-R-seau-Multi-sites

- Ouvrez le fichier .pkt.

- Effectuez un Ping depuis un PC du site Abidjan vers le Serveur Web du site Nice pour vérifier la connectivité.




## License

[MIT](https://choosealicense.com/licenses/mit/)

