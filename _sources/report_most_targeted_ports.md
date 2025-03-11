# Most Targeted Ports by Attacks

![Attack Chart](chart3.png)

Ce **graphique en barres horizontales** indique les **ports les plus ciblés** (445, 23, 22, 8728, 2323) et le volume 'attaques associé.

## Notes
- Le port **445** (SMB) domine ici avec plus de 9k attaques, suggérant que des vulnérabilités (ex: MS17-010) sont encore massivement exploitées.
- Les ports **23/2323** (Telnet) et **22** (SSH) sont souvent visés par des bots qui tentent des connexions brute force ou exploitent des identifiants par défaut.
- **8728** (routeros) révèle une tendance ciblant les routeurs Mikrotik, susceptibles de servir de rebond poud'autres attaques.
