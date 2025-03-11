# Attack Protocol Distribution

![Attack Chart](chart2.png)

Ce camembert (pie chart) représente la répartition des attaes en fonction du protocole applicatif (`app_proto`).

## Notes
- Les protocoles les plus visés reflètent les services souvent cle :
  - **smb (445)** : attaqué pour diffuser des ransomwares ou exécuter des exploits comme EternBlue.
  - **telnet (23, 2323)** : couramment exploité pour pénétrer des systèmes IoT mal configurees.
  - **routeros (8728)** : représente les attaques visant des routeurs Mikrotik.
  - **ssh (22)** : cible privilégiée pour brute force ou keylogg.
- Le volume de chaque protocole indique où concentrer les mesures de sécurité (mises à jour, correctifs, règles de age).
