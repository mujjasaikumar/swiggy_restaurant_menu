
# Swiggy Restaurant Menu Scraper

This Python script allows you to scrape the menu of a restaurant from Swiggy using restaurant_ID and save it as a CSV file.

## Features

- Scrapes the menu of a specified restaurant from Swiggy.
- Converts the scraped data into a structured CSV file.
- Supports extraction of dish names, categories, descriptions, and prices.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/mujjasaikumar/swiggy_restaurant_menu.git
    ```

2. Install the required Python packages:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Open `main.py` in a text editor.
2. Replace the `restaurant_ID` variable with the ID of the restaurant you want to scrape.
3. Run the script:

    ```
    python main.py
    ```

4. The scraped menu will be saved as a CSV file with the restaurant name.

## Custom Error Handling

If the restaurant data is not present, the script will throw a custom error to notify the user.

## Requirements

- Python 3.x
- requests
- pandas

## Contributors
- Saikumar Mujja


---
