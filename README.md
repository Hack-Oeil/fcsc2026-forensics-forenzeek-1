# FCSC 2026 Forenzeek - Compromission initiale

Des logs réseau issues de [l’outil Zeek](https://docs.zeek.org/en/master/scripts/base/protocols/conn/main.zeek.html#type-Conn::Info) ont été collectés sur un réseau dans lequel un attaquant a été repéré. Seule une partie des champs des logs de Zeek sont diponibles.

Une compromission a été observée sur la machine dont l’adresse IP est 192.168.1.42. Cette compromission a été réalisée via un email malveillant contenant une charge utile assez volumineuse. Pouvez-vous retrouver l’uid de la connexion associée au téléchargement du mail ? (ex: 1ac41a8ff0fd305679)

Le flag est au format `FCSC{uid}` (ex. `FCSC{1ac41a8ff0fd305679}`)

Auteur : mln

Origine : [Forenzeek - Compromission initiale](https://hackropole.fr/fr/challenges/forensics/fcsc2026-forensics-forenzeek-1/)


## Challenge
[files/forenzeek.csv.gz](files/forenzeek.csv.gz)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2026-forensics-forenzeek-1.git

> cd fcsc2026-forensics-forenzeek-1


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2026-forensics-forenzeek-1/
