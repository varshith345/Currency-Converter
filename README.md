# Currency Converter

## Description

This project is a currency converter web application built with HTML, CSS, and JavaScript. It uses an API to fetch real-time exchange rates, enabling users to convert amounts from one currency to another accurately and quickly.

## Features

- Convert amounts between multiple currencies
- Fetch real-time exchange rates from a reliable API
- Simple and intuitive user interface
- Responsive design for mobile and desktop use

## Demo

[Live Demo](https://varshith345.github.io/Currency-Converter/)

## Screenshots

![Currency Converter Screenshot](https://imgur.com/a/tgTefO6)

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/currency-converter.git
    ```

2. Navigate to the project directory:

    ```bash
    cd currency-converter
    ```

3. Open `index.html` in your preferred web browser to run the application.

## Usage

1. Enter the amount you want to convert.
2. Select the currency you want to convert from.
3. Select the currency you want to convert to.
4. Click the "Get Exchange Rate" button to see the converted amount.

## API

This project uses the [ExchangeRate-API](https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api@1/latest/currencies/) to fetch real-time exchange rates. You need to sign up for a free API key and replace `YOUR_API_KEY` in the `script.js` file with your actual API key.

## Code Overview

### HTML

The `index.html` file contains the structure of the web application, including input fields, dropdown menus for currency selection, and the convert button.

### CSS

The `styles.css` file contains styles to enhance the appearance and layout of the application.

### JavaScript

The `script.js` file contains the logic to interact with the exchange rate API and update the UI based on user inputs.

