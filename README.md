# -Säkra IT-infrastruktur för produktion
Kursen IT-infrastruktur är mycket intressant.
Jag planerar att bygga en IT-infrastruktur för ett företag med anläggningar i Linköping och Norrköping, data ska synkroniseras helt mellan två virtuella datorer.
Infrastrukturen ska inkludera olika webbservrar på olika virtuella maskiner och jag kommer att prioritera säkerhet och tar inte hänsyn till företagets ekonomi.


En komponentlista...



1- En publik IP
En publika IP-adress för extern åtkomst till tjänster.

2- Operativsystem
Kommer att använda Linux baserade datorer, ubuntu, debian eller mint

3- Sårbarheter i IT-infrastruktur, Router och Brandvägg
Vill använda säkra brandväggar med avancerade säkerhetsfunktioner (NGFW - Next Generation Firewalls).
Tänker på att använda nftables
https://medium.com/@diyar.parwana/nftables-for-uslinux-administrators-a-simple-guide-d13c5f0cf40f

4- Switchar
Kommer att använda switchar

5- Virtualiseringsverktyg
Virtualiseringsverktyg, virtualbox, qemu och VMware eller Hyper-V för att skapa och hantera virtuella maskiner.

6- Lagringslösningar
Kan tänka mig använda en  NAS (Network Attached Storage) för delad lagring
Implementering av  RAID-konfigurationer för redundans Säkerhetskopiering...

7- LDAP, istället för active directory

8- Applikationsnivå
load balancers, proxy server, nginx, apache, egna tidigare bash skripter

9- Övervakning och förvaltning
Skriva bash skripter för att automatiskt bevaka kommande datatrfik via öppna portar.



- Automatiserade installationer av apache server
- https://github.com/diypa571/silviastack

- Behöver bli bättre på LDAP.
  




