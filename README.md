# Daily Temperature Analysis using NumPy

A light, hands-on data analytics project analyzing multi-city daily temperature variations across Nigeria using Python and NumPy. This project demonstrates  array operations to compare regional weather data, track peak temperature locations, and perform scalar math without explicit Python loops.


## Features

- **Daily Peak Temperature Tracking:** Identify the warmest city for each recorded day using vectorized matrix maximums (`np.maximum`) and conditional selection (`np.where`).
- **Simulated Climate Shifts:** Apply element-wise scalar operations to simulate uniform temperature increases.
- **Regional Comparative Analysis:** Calculate daily thermal differentials between major urban centers (Lagos vs. Abuja).
- **Array Inspection:** Validate shape and data types (`float64`) across all temperature series.


## Dataset Reference

The analysis evaluates a 5-day temperature sequence (°C) recorded across three primary Nigerian cities:

| City | Day 1 | Day 2 | Day 3 | Day 4 | Day 5 | Mean Temp (°C) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Lagos** | 27.5 | 29.0 | 30.5 | 28.0 | 31.0 | 29.2 |
| **Abuja** | 25.0 | 28.0 | 29.5 | 30.0 | 32.0 | 28.9 |
| **Ibadan** | 26.5 | 28.5 | 29.0 | 27.5 | 30.5 | 28.4 |

---

### Prerequisites

- Python 3.x
- NumPy





## Project Structure

```text
├── hands_on_practice_14.ipynb   # Main Jupyter Notebook containing analytics workflow
├── main.py                     # Python script implementation of the analysis
├── README.md                   # Project documentation
└── requirements.txt            # Project dependencies
