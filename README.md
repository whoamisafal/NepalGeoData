# Nepal Municipalities Dataset

## Overview

This dataset contains information about municipalities and their wards in Nepal. The data includes details such as the country, state, district, municipality name, and the wards under each municipality.

## Structure

The dataset is represented in JSON format, where each entry provides information about a municipality, including the following fields:

- **_id**: A unique identifier for each municipality entry.
- **country**: The country to which the municipality belongs.
- **state**: The state/province in which the municipality is located.
- **district**: The district of the municipality.
- **municipality**: The name of the municipality.
- **wards**: A list of integers representing the wards within the municipality.

### Example Entry

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
    1,
    2,
    3,
    4,
    5,
    6,
    7,
    8,
    9,
    10,
    11,
    12,
    13,
    14
  ]
}
#   N e p a l G e o D a t a  
 