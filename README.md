# Star Wars Postman Collection

This Postman collection fetches data from the [Star Wars API](https://swapi.py4e.com/), retrieves a specific person (e.g., Luke Skywalker), and loops through their vehicles to display the names.

## How to Use

1. Import `StarWarsVehicles.postman_collection.json` into Postman.
2. Run the `Init` request to load vehicle data.
3. Use the **Collection Runner** to run both:
   - `Init`
   - `Get Vehicle`
4. Watch the Postman Console to see vehicle names appear in order.

## Requirements

- Postman v11+
- Internet access (uses `https://swapi.py4e.com/`)
