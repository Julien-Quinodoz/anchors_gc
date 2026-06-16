# anchors_gc

Configuration des ancres spatiales Meta par salle.

## Fichier `anchors.json`

| Champ | Description |
|---|---|
| `SalleA` | UUID de l'ancre cloud Meta — Salle A |
| `SalleB` | UUID de l'ancre cloud Meta — Salle B |
| `updatedAt` | Date de dernière mise à jour |

## URL pour Unity (raw)

```
https://raw.githubusercontent.com/Julien-Quinodoz/anchors_gc/main/anchors.json
```

## Mise à jour après recalibration

1. Calibrer la nouvelle ancre avec l'outil Quest
2. Remplacer l'UUID correspondant dans `anchors.json`
3. Commit sur GitHub — pas de rebuild des jeux nécessaire
