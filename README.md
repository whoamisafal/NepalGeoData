# 🏞️ Nepal Municipalities Dataset

### 📋 Overview

This dataset provides detailed information about municipalities in Nepal, including their administrative divisions and ward-level structures. It includes data such as country, state, district, municipality name, and a list of wards within each municipality.

### 🗂️ Structure

The dataset is in JSON format, and each entry contains the following key fields:

- **_id**: Unique identifier for each municipality.
- **country**: The country of the municipality (e.g., Nepal).
- **state**: The state or province where the municipality is located (e.g., Koshi Province).
- **district**: The district of the municipality (e.g., Bhojpur).
- **municipality**: Name of the municipality (e.g., Shadanand Municipality).
- **wards**: A list of ward numbers in the municipality.

### 💡 Example Entry

```json
{
  "_id": {
    "$oid": "66e6c2611c0fd1a8af18d8ae"
  },
  "country": "Nepal",
  "state": "Koshi Province",
  "district": "Bhojpur",
  "municipality": "Shadanand Municipality",
  "wards": [
    1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14
  ]
}
