# T-Pot Attack

![Attack Chart](chart1.png)

Ce graphique en barres montre le nombre total d'attaques par adresse IP (`event_count`).
L'objectif est d'identifier les IP les plus actives (et potentiellement les plus malveillantes).

## Notes

- Une IP avec un volume d'attaques élevé indique souvent un botnet, un scanner automatique ou un acteur malveillant ciblant massivement les ports vulnérables.
- Dans notre cas, on observe que `54.37.81.238` et `46.105.70.190` dépassent 6000 attaques, ce qui mérite une enquête approfonetc.).
- Les IP ayant un event_count plus faible ne sont pas nécessairement inoffensives, mais peuvent correspondre à des scans ponctuels ou à des tentatives ce.
