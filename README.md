# Resale Flat Price Analysis 📊

A Python script that processes resale flat price data (from 2017 - 2024) to:
- Determine the **lowest** resale price for a specific town in a given year.
- Identify towns with the **highest and lowest maximum resale prices** in a given year.

## How It Works
1. Reads a CSV file containing flat resale prices.  
2. Uses filtering and mapping functions to extract relevant data.  
3. Computes and returns the desired statistics.  

## How To Run
Ensure that "Resale_flat_prices.csv" is in the same folder as the python file

Run:
```python
year_lowest_resale("Resale_flat_prices.csv", "town_name", year)
```
or
```python
town_high_low_resale(year, "Resale_flat_prices.csv")
```
after inputting your desired *town_name* or *year* in the respective placeholders.
