# Chestshops (Kistenshops)

Mit einem Chestshop verkaufst oder kaufst du Items automatisch, ohne selbst online sein zu müssen – über eine Kiste auf deinem Plot mit einem beschrifteten Schild davor.

## Einrichten

1. Kiste auf deinem Plot platzieren.
2. Optional: Die Items, die verkauft/angekauft werden sollen, in die Kiste legen.
3. Ein Schild direkt an der Kiste anbringen und wie folgt beschriften:

| Zeile | Inhalt |
|---|---|
| 1 | *(leer lassen)* |
| 2 | Menge an Items pro Vorgang |
| 3 | `B [Ankaufpreis] : [Verkaufpreis] S` |
| 4 | `?` oder der Item-Name |

**Beispiel** – 32 Diamanten, Ankauf für 1, Verkauf für 3:

```
32
B 1 : 3 S
DIAMOND
```

## Nur Ankauf oder nur Verkauf

Du musst nicht beides anbieten:
- Nur ankaufen: `B 1`
- Nur verkaufen: `S 3`

## Item automatisch erkennen (`?`)

Schreibst du in Zeile 4 ein `?` statt eines Item-Namens, wird automatisch das Item eingesetzt, das entweder in der Kiste liegt oder das du gerade in der Hand hast, wenn du das Schild rechtsklickst.

## Bekanntes Problem bei alten Plots

Plots, die **vor dem 09.07.2026** erstellt wurden, haben meistens nicht den richtigen Flag gesetzt, damit auch nicht-getrustete (fremde) Spieler den Chestshop bedienen können. Betroffen? Melde dich im [Discord](https://dc.cubetown.de) im Support – dort wird dir geholfen.
