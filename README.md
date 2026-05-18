# Wohnungskauf-Rechner (Apartment Cost Calculator)

A comprehensive calculator for estimating apartment purchase costs in Germany. This tool helps you calculate the total cost of buying an apartment including purchase price, taxes, fees, and financing options.

## Features

- **Cost Calculation**: Calculate purchase price, transfer tax (Grunderwerbsteuer), notary fees, and broker fees
- **Financing Analysis**: Estimate mortgage payments and total interest
- **Visual Breakdown**: Interactive charts showing cost distribution
- **German Market**: Tailored for German real estate market calculations
- **Responsive Design**: Works on desktop and mobile devices

## How to Run

### Option 1: Direct File (No Installation Required)
Simply open the `wohnungskauf-rechner.html` file in your web browser:
1. Download or clone this repository
2. Double-click `wohnungskauf-rechner.html` or open it with your browser
3. Enter your apartment details and start calculating

### Option 2: Using a Local Server
For best performance, serve the file through a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000/wohnungskauf-rechner.html` in your browser.

## Usage

1. Enter the **purchase price** of the apartment
2. Select the **state** (Bundesland) to apply correct transfer tax rates
3. Enter any **additional costs** (broker fees, renovations, etc.)
4. View the **cost breakdown** and **financing options**
5. Adjust mortgage parameters to see different scenarios

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses Chart.js for visualizations
- No external dependencies (aside from CDN resources)
- Responsive design using modern CSS

## Browser Compatibility

Works on all modern browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge

## License

See LICENSE file for details.
