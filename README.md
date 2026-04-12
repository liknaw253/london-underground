# London Underground Data

Geographic and schematic data for the London Underground, DLR, and Elizabeth line networks.

## Data

All files are in `data/` as JSON.

| File | Description |
|------|-------------|
| `tube-stop-names.json` | Mapping of 360 station IDs to human-readable names |
| `tube-stops.json` | Station IDs mapped to `[latitude, longitude]` coordinates |
| `tube-schematic.json` | Schematic (diagram) coordinates for each line's route, keyed by line name |
| `tube-shapes.json` | Geographic route shapes for each line, keyed by line name |

### Lines

bakerloo, central, circle, district, hammersmith-city, jubilee, metropolitan, northern, piccadilly, victoria, waterloo-city, dlr, elizabeth

### Station IDs

Stations use TfL NaPTAN identifiers (e.g. `940GZZLUBST` for Baker Street).
