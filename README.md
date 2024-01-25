
# Lithuanian Real Estate Listings

## Description
This repository contains a comprehensive dataset of real estate listings in Lithuania, currently featuring apartment data from aruodas.lt as of January 2024. In the future, this repository will be expanded to include various types of properties (houses, land, etc.) and data from various providers.

## Repository Structure
```
lithuanian-real-estate-listings/
│
├── data/
│   ├── apartments/
│   │   └── all_cities_20240125.csv
│   ├── houses/ (coming soon)
│   ├── land/ (coming soon)
│   └── ... (additional categories)
│
├── scripts/ (if applicable)
│   └── ...
│
├── docs/
│   └── ...
│
└── examples/ (if applicable)
    └── ...

```

## Data Example and Statistics
The `data/apartments/all_cities_20240125.csv` file contains detailed listings of apartments across various cities in Lithuania. Below are some statistics and a sample of the dataset:

- **Dataset Overview:**
  - Total Listings: 7,152
  - Columns: 18 (including area, build year, price, etc.)
  - Price Range: 15 to 2,500,000
  - Number of Rooms: 1 to 13
  - Column Headers: unique_id, type_id, area, build_year, building_type, coordinates, equipment, floor, heating_system, microdistrict, no._of_floors, number_of_rooms, price, region, renovation_year, street, url, image_urls

- **Building Types:**
  - Majority are Brick (4,956) and Block House (1,706)

- **Price Trends:**
  - Average prices increase with the number of rooms, ranging from around 62,214 for 1 room to 1,017,000 for 13 rooms.

- **Sample Data:**
  - Example Listing 1: Unique ID 3396605, Area 66.04 sqm, Built in 2016, Brick Building, Located at 54.6788,25.25887, Fully equipped, 3rd floor
  - Example Listing 2: Unique ID 3398277, Area 23.00 sqm, Built in 2005, Brick Building, Located at 54.01401,23.98115, Partially equipped, 2nd floor

## How to Use
- Download the desired CSV files from the `data/` directory.
- Load the data using a CSV reader in your preferred programming language or software.
- Refer to the `examples/` directory for sample code and analysis (if available).

## License
This dataset is made available under the [Attribution-NonCommercial 4.0 International license](LICENSE). By using this data, you agree to the terms of this license.

---


*This README is subject to updates as the repository grows and evolves.*
