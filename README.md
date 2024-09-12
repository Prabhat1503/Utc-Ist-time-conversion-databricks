# Databricks-utc-ist-time-conversion


## Overview

This repository contains a PySpark script that demonstrates how to process timestamp data in Databricks. The script performs the following operations:
1. Loads a CSV file into a PySpark DataFrame.
2. Updates a date column with random times.
3. Converts the updated timestamp to UTC and IST.

## Project Structure

- **`process_csv_timestamps.py`**: Contains the Python script for processing timestamps.

## Setup in Databricks

### 1. Create a Databricks Notebook

1. **Log in to your Databricks workspace.**
2. **Create a new notebook**:
   - Click on `New` > `Notebook`.
   - Name your notebook and choose `Python` as the language.

### 2. Copy and Paste the Code

Copy the contents of `process_csv_timestamps.py` and paste it into your Databricks notebook.

### 3. Run the Code

- Execute the notebook to load the CSV file, update the timestamp, and convert it to UTC and IST.

  ![image](https://github.com/user-attachments/assets/fe8f8840-3fef-403c-bb35-61ca2d53c8f6)


## Dependencies

Ensure that the following packages are installed in your Databricks environment:
- PySpark (typically included in Databricks)

## Notes

- Modify the CSV file path (`/FileStore/tables/Sales_SalesOrderDetail-1.csv`) as needed.
- The random time generation function creates random times in the format `HH:MM:SS`.
- UTC to IST conversion assumes a fixed offset of +5:30.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
