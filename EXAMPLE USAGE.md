# 🏞️ Nepal Municipalities Dataset

### 📋 Overview

This project contains a dataset of municipalities in Nepal, along with a simple Python script to load and access this data. The dataset includes key information about the municipalities, such as their names, district, and the wards within each municipality.

### 🛠️ Python Script

The provided Python script reads the `nepal_municipalities.json` file and prints the name of the first municipality.

### 📂 Files

- `nepal_municipalities.json`: The dataset containing information about municipalities in Nepal.
- `load_dataset.py`: Python script to load the dataset and print the name of the first municipality.

### 📝 Python Script Example

Below is the code to load and access the first municipality:

```python
import json

# Load the dataset from a JSON file
with open('nepal_municipalities.json') as file:
    data = json.load(file)

# Access the first municipality's name
print(data[0]['municipality'])  # Output: Shadanand Municipality
