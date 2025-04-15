# Data Logger for Sensor Readings

This project is built to record real-time data from sensors and store it in a simple and readable format. It's designed to help with experiments, monitoring tasks, or any setup where you need to track sensor values over time.

## What it Does
- Reads sensor values using Arduino
- Sends data to Python via serial communication
- Saves the data into a CSV file for easy access and analysis

## Tools & Technologies
- **Arduino** – for collecting sensor readings
- **Python** – for reading serial data and saving to file
- **CSV** – for data storage

## How to Use
1. Connect your sensor to the Arduino
2. Upload the Arduino code from this repo
3. Run the Python script (`logger.py`)
4. Sensor readings will be automatically saved to a CSV file

## Key Files
- `logger.py` – handles the serial connection and logging
- `description.md` – contains the overview of the project
- `LICENSE` – open-source license for reuse

## Created By
**Nezami**  
GitHub: [@nezamimdkaif](https://github.com/nezamimdkaif)

