# Geography Data

A collection of geographic reference data including country information and US city data.

## Contents

### Country Data

- **countries.tsv** - Comprehensive country information including:
  - Country names
  - ISO 2/3 letter codes
  - ISO numeric IDs
  - IOC codes
  - FIPS 10 codes
  - License plate codes
  - Country domains

- **country-aliases.tsv** - Common country name aliases mapped to their IOC codes

### US Cities

- **zipcodes/uscities.csv** - Detailed US cities database

## Data Sources

- Country data: https://www.worlddata.info/countrycodes.php
- US cities: https://simplemaps.com/data/us-cities

## Setup

To get the latest US cities data:

1. Download uscities.csv from https://simplemaps.com/data/us-cities
2. Extract and place in the `zipcodes/` directory

## File Format

All data files use tab-separated values (TSV) format for easy parsing and compatibility.
