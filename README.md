# Strasbourg Commute Map

How easy is it to get to a given place from each neighbourhood of Strasbourg?

The user chooses a destination (their university, their job, their gym...) and the map shows the public transport travel time from every neighbourhood of Strasbourg to that place. The goal is to help people, especially students, choose where to live: a neighbourhood further away can be a better choice than a closer one if it has a direct tram line.

## Status

Work in progress.

## Roadmap

- [ ] V1: travel time by public transport (CTS) from each neighbourhood to one chosen destination, shown on a map
- [ ] Number of transfers and service frequency
- [ ] Late-evening service (last tram/bus)
- [ ] Cycling alternative
- [ ] V2: two destinations (e.g. university + part-time job) to find neighbourhoods convenient for both

## Data

- CTS timetables (GTFS) - open data
- Neighbourhood boundaries - data.strasbourg.eu
- OpenStreetMap

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
