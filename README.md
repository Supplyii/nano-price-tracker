# Nano Price Tracker

This is a simple web application that tracks the price of Nano (NANO) cryptocurrency in USD and INR. It provides real-time updates on the current price and indicates whether the price has increased or decreased since the initial price.

## Features

- Displays the current price of Nano in USD and INR
- Shows the initial price of Nano
- Indicates whether the current price has increased or decreased using a color-coded indicator

## Usage

1. Open the `index.html` file in a web browser.
2. The initial price and current price will be displayed as "Loading..." until the data is fetched.
3. The page will automatically update the price every 5 seconds.
4. The indicator will be green if the current price is equal to or higher than the initial price, and red if it is lower.

## Technologies Used

- HTML
- CSS
- JavaScript

## API Used

This application uses the CoinGecko API to fetch the current price of Nano in USD and INR. The API endpoint used is: 
https://api.coingecko.com/api/v3/simple/price?ids=nano&vs_currencies=usd,inr


## Credits

This application is created by supplyii. You can find the code and more projects on(https://github.com/supplyii).

If you have any questions or feedback, feel free to contact me on github
