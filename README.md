# Hotel Tutorial — Starter Repo

Hands-on 90-minute Python-for-data tutorial. Everyone works in one Colab notebook
against `hotel_bookings.csv`.

## Files
- `hotel_tutorial.ipynb` — the tutorial (open in Colab).
- `hotel_bookings.csv` — the shared dataset (~119k hotel bookings).
- `requirements.txt` — pinned dependencies.

## About the dataset
Based on the public Hotel Booking Demand dataset, with four columns added for the
weather section: `hotel_name`, `hotel_city`, `latitude`, `longitude`. Each booking is
assigned a fictional named property with real coordinates, derived from the guest's
country and hotel type (City Hotels -> a city; Resort Hotels -> the coast). This is
deliberate fiction so the Open-Meteo lookups point at varied, real locations.

## Before the session (pre-work)
1. Have a GitHub account and a **personal access token (PAT)** ready for the Git block.
2. Open the notebook in Colab: replace `CSV_URL` in the data-loading cell with this repo's
   raw CSV link, e.g.
   `https://raw.githubusercontent.com/YOUR-ORG/hotel-tutorial/main/hotel_bookings.csv`

## Run order
Open `hotel_tutorial.ipynb` and run cells top to bottom. If anything looks wrong:
**Runtime ▸ Restart and run all.**
