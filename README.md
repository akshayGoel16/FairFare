# Cab Price Comparator — *FairFare*

**FairFare** is a Python-based cab fare comparison tool that helps users find the **cheapest ride option** between Ola Mini, Rapido Car, and Uber Go. With a user-friendly Streamlit interface and real-time price filtering, this app offers an easy way to make cost-effective travel decisions.

---

## Features

- Compare fares from **Ola Mini**, **Rapido Car**, and **Uber Go**
- Select **Pickup** and **Destination** locations from a dropdown
- Choose **hour of travel** and get time-matched price data
- Highlights the **cheapest available cab**
- Clean and interactive data table with fare details
- Expandable "How it works" section for new users

---

## Tech Stack

- **Python 3**
- **Streamlit** for interactive web UI
- **Pandas** for data manipulation
- **CSV File** as backend data source

---

## Dataset (cab_price.csv)

The dataset used contains the following columns:

- `Pickup Location`
- `Destination`
- `Time of Day`
- `Ola Mini`
- `Rapido Car`
- `Uber Go`

---

## How It Works

1. User selects **pickup**, **destination**, and **hour** of travel.
2. The app filters the dataset for matching routes.
3. Finds the **closest time entry** (within 2 hours).
4. Compares prices from Ola, Rapido, and Uber.
5. Displays fare table and highlights the **cheapest cab**.
6. Provides a simple explanation for first-time users.

---

## Running the App

To run the app locally:

```bash
pip install streamlit pandas
streamlit run your_script_name.py (Ex: app.py)
