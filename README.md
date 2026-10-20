## Plan d'adressage

| Réseau | Plage | Passerelle | Usage |
|---|---|---|---|
| VLAN 10 ADMIN | 192.168.10.0/24 | 192.168.10.1 | Direction, informatique |
| VLAN 20 COMPTA | 192.168.20.0/24 | 192.168.20.1 | Comptabilité |
| VLAN 30 SERVEURS | 192.168.30.0/24 | 192.168.30.1 | SRV-DNS 192.168.30.10 |
| VLAN 99 GESTION | 192.168.99.0/24 | 192.168.99.1 | Administration des équipements |
| Agence (R2) | 192.168.40.0/24 | 192.168.40.1 | Site distant |
| Lien R1-R2 | 10.0.12.0/30 | — | OSPF |
| Lien R1-FAI | 203.0.113.0/30 | 203.0.113.2 | Sortie Internet (plage de documentation) |
| « Internet » | 198.51.100.0/24 | 198.51.100.1 | Serveur web externe 198.51.100.10 |
