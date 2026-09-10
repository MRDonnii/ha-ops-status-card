# Ops Status Card

Et selvstændigt, tema-kompatibelt Lovelace-kort til Home Assistant. Kortet er flyttet fra en aktiv installation til et separat repository, så kildekode og versionshistorik kan vedligeholdes sikkert.

## Installation

Kopiér `ha-ops-status-card.js` til `/config/www/ha-ops-status-card/` og registrér ressourcen som et JavaScript-modul:

```text
/local/ha-ops-status-card/ha-ops-status-card.js?v=0.2.0
```

Tilføj derefter korttypen `custom:ha-ops-status-card` i Lovelace. De nødvendige entities angives i kortets konfiguration; repositoryet indeholder ingen installationens dashboardkonfiguration eller personlige data.

## Udvikling

```bash
npm run check
```

## Licens

MIT
