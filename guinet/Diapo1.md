# The virtualization foundations

## Introduction

But de la virtualisation

- Optimiser et mutualiser les resources
- Consolider IT
- Indé: hardware
- Améliorer: disponibilité et scalabilité
- Automatisation
- Réduction de cout

Niveau de virtualisation

- Stockage: 
  - Indé emplacement, fléxible, optimisation de l'espace
  - Storage Pools, vSAN
- Réseau
  - Fléxible, Sécurité, Isolation, Performance
  - vLAN, vSwitch
- OS
  - Disponible, Scalable, Performance
  - Hyperviseur
- Session
  - Mutualisation des resources
  - SBC/VDI solutions: RDS, AppliDis, Cirtix
- Application:
  - Streaming, Isolation des resources
  - Bubble container Applications
- Environement d'exécution
  - Isolation des applications, Sécurité, Mobilité
  - Container
- Utilisateur
  - Os indé, Performance
  - Streaming, Applications tiers



Fonctionnement:

- Traditionnel: 1 machine, 1 OS, x app, > 25%
- VM: 1 machine, 1hyperviseur, X OS, Y App, < 75%

VM = emulation des resources



## Virtualization main actors

- VMware
- Microsoft
- Nutanix
- VirtualBox
- Xen
- KVM

Applidis agis au niveau => application/session et utilisateur



## Virtualization prerequisites

Vitualisation => x64 CPU et BIOS support la Virtualisation

## Main access protocols

Utiliser le RDP agit sur 7 à 4 du modéle OSI

Modéle OSI:

- 7 Application
- 6 Presentation
- 5 Session
- 4 Transaport
- 3 Réseau
- 2 Data Link
- 1 Physique

Stream envoyé au client, interface physique envoyé au serveur

## Types of virtualization

1. Virtualisation d'application
2. Virtualisation standart du Desktop => OS server
3. Virtualisation étendue du Desktop => workstation OS

## Architecture

- Broker/Balancer: Intélligence du système. Redirection de l'utilisateur vers les serveurs de Virtu
- Console d'administration: permet la gestion pour les admins. App ou app web
- User portail/access: utilisateur accéder à la virtualisation.
- Applications: Délivrer avec la virtu
- DataBase/DataStore: configuration de la solution de virtu
- Directory: authentifie les utilisateurs, gére les groupes
- Gateway: méthode de connexions
- Hypervisor: 

