# Plot-Verwaltung

Wer was auf deinem Plot darf, steuerst du selbst:

| Befehl | Wirkung |
|---|---|
| `/plot add <spieler>` | Spieler als **Mitglied** hinzufügen – darf bauen, solange du online bist |
| `/plot trust <spieler>` | Spieler als **vertraut** einstufen – darf bauen, auch wenn du offline bist |
| `/plot remove <spieler>` | Mitglied/Vertrauten wieder entfernen |
| `/plot deny <spieler>` | Spieler das **Betreten verbieten** |
| `/plot undeny <spieler>` | Verbot wieder aufheben |
| `/plot kick <spieler>` | Spieler sofort vom Plot werfen |

## Flags

Mit `/plot set flag <flag> <wert>` lassen sich Regeln pro Plot einstellen, z. B.:

- `pvp` – PvP auf dem Plot erlauben/verbieten
- `mob-spawning` – Mobspawns auf dem Plot an/aus
- `keep-inventory` – Inventar bei Tod auf dem Plot behalten
- `explosion` – Explosionen (TNT, Creeper) erlauben/verbieten

Alle verfügbaren Flags: `/plot flag list`

> ✏️ **TODO:** Tatsächlich aktive Flags und ggf. abweichende Standardwerte auf CubeTown ergänzen.
