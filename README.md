<h1 align="center">TP pfSense</h1>

<p align="center">
  Comptes rendus de TP réalisés sur pfSense : DMZ, monitoring et accès distant.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/pfSense-2.9.0-blue" alt="pfSense">
  <img src="https://img.shields.io/badge/Proxmox-VE-orange" alt="Proxmox">
  <img src="https://img.shields.io/badge/BTS-SIO%20SISR-green" alt="BTS SIO SISR">
</p>

## Sommaire

| Partie | Contenu | Compte rendu |
|---|---|---|
| 1 | Architecture DMZ : installation de pfSense, serveur web LAMP, NAT et règles de pare-feu | [Ouvrir](TP1-pfSense-DMZ/README.md) |
| 2 | Addon : monitoring du LAN avec ntopng et bureau à distance (RDP) depuis Internet | [Ouvrir](TP2-pfSense-RDP/README.md) |

## Technologies utilisées

| Rôle | Outil |
|---|---|
| Virtualisation | Proxmox VE |
| Pare-feu / routeur | pfSense CE |
| Serveur web | LAMP (conteneur LXC) |
| Monitoring | ntopng |
| Accès distant | RDP (Windows Server 2016) |
