Data used for [Portal Kombat](https://portkom.rknight.me)

- `yachts.json`: A list of boats docked in Gosport Marina on 2025-03-28
- `ships.json`: List of ships from Portsmouth International Port
- `ships-types.json`: Distinct types, ports, countries, and matching emoji from `ships.json`
- `movements.json`: Movements of ships in and out of Portsmouth International Port 2023
- `movements-types.json`: Distinct names, from, to, and berths from `movements.json`, plus calculated attributes:
    - `timeInPort`: Combined time in port (in minutes) across all visits
    - `timeInPortHours`: Human readable time in port
    - `visits`: Number of port visits
    - `berths`: Which berths the ship visited, how many times, and favourite (most visits)
    - `nationality_emoji`: Emoji for the home country of the ship
- `images`: an image for each ship in `combined.json`. Format: `{lrn}.jpg`