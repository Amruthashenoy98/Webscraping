
# Webscraping to collect data from Ajio and Smartprix websites
*The web scraping in this project was done using Selenium and Beautiful Soup.*
## Bag Dataset from Ajio

This dataset contains information about different bags from various brands, scraped from the Smartprix website. The dataset includes details such as brand, style, original price, and offer price.

### Columns

- **brand**: The brand of the bag.
- **style**: The style or type of the bag.
- **price**: The original price of the bag in Indian Rupees (INR).
- **offer_price**: The discounted offer price of the bag in Indian Rupees (INR). Some entries might have NaN values if no offer is available.

### Usage

This dataset can be used for various purposes such as:

- Analyzing trends in bag prices across different brands.
- Comparing original prices with offer prices to find discounts.
- Exploring popular bag styles and brands.

### Sample Data

| brand           | style                                               | price   | offer_price |
|-----------------|-----------------------------------------------------|---------|-------------|
| ARMANI EXCHANGE | Wave Classic Hobo Bag                               | ₹11,999 | ₹10,199     |
| Miraggio        | Solid Tote Bag                                      | ₹3,374  | ₹3,074      |
| Puma            | X Anushka Tote Bag with Detachable Strap            | ₹1,600  | ₹1,240      |
| Dune London     | E'Bug Evening Bag                                   | ₹5,600  | ₹4,480      |
| Mini Wesst      | Women Quilted Tote Bag                              | ₹1,700  | NaN         |
| ...             | ...                                                 | ...     | ...         |

### Notes

- The prices are in Indian Rupees (INR).
- Some offer prices might be NaN, indicating no discount or offer.
- This dataset was created by webscraping the Smartprix website.

## Smartphone Dataset from Smartprix

This dataset contains information about various smartphones from different brands, scraped from the Smartprix website. The dataset includes details such as brand, price, and user rating.

### Columns

- **brand**: The brand of the smartphone.
- **price**: The price of the smartphone in Indian Rupees (INR).
- **rating**: The user rating of the smartphone out of 5.

### Usage

This dataset can be used for various purposes such as:

- Analyzing smartphone prices across different brands.
- Investigating the relationship between price and user ratings.
- Identifying popular smartphones based on user ratings.

### Sample Data

| brand                  | price   | rating |
|------------------------|---------|--------|
| OnePlus Nord CE 4 5G   | ₹24,843 | 4.2    |
| Motorola Edge 50 Pro 5G| ₹31,999 | 4.7    |
| Infinix Note 40 Pro 5G | ₹21,999 | 4.25   |
| Vivo T3 5G             | ₹19,999 | 4.7    |
| Samsung Galaxy M55     | ₹26,999 | 4.55   |
| ...                    | ...     | ...    |

### Notes

- The prices are in Indian Rupees (INR).
- Ratings are based on user reviews.
- This dataset was created by webscraping the Smartprix website.

Feel free to explore and analyze this dataset!

