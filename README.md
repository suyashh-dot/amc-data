# amc-data

Data repository for [AMC Portfolio Intelligence](https://suyashh-dot.github.io/amc-tracker).

This repo is updated monthly via `update.py` in the `amc-tracker` repo.

## Files

| File | Description |
|------|-------------|
| `metadata.json` | Latest month, total counts, available months list |
| `compressed_data.json` | All instrument → fund → weight data |
| `fund_data.json` | All fund → instrument → weight data |
| `signals.json` | Fresh bets & exit alerts per month |
| `sector_rotation.json` | Sector allocation trends |
| `first_mover.json` | Fund entry progression per instrument |
| `sector_map.json` | Instrument → sector classification |
| `users.json` | Login credentials (hashed passwords) |

## Update

See `amc-tracker/README.md` for monthly update instructions.
