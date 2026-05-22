# Currency Converter 💱

A simple, elegant, and real-time currency converter web application that allows users to convert between different world currencies with live exchange rates.

## Features ✨

- **Real-time Exchange Rates**: Fetches live currency exchange rates from a reliable API
- **Currency Swap**: Quickly swap between "from" and "to" currencies with a single click
- **Flag Display**: Shows country flags alongside currency codes for better visual identification
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Beautiful UI**: Modern gradient background with smooth animations and transitions
- **User-Friendly**: Intuitive interface with clear labeling and helpful visual feedback

## Screenshots 📸

The application features:
- Input field for amount conversion
- Dropdown menus for selecting currencies
- Real-time exchange rate display
- Swap button with rotation animation
- Country flag icons for each currency

## Technologies Used 🛠️

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling, animations, and responsive design
- **JavaScript (ES6+)**: Core functionality and API integration
- **External APIs**:
  - [fawazahmed0 Currency API](https://github.com/fawazahmed0/currency-api) - For exchange rates
  - [Flags API](https://flagsapi.com/) - For country flag images

## Project Structure 📁

```
Currency-Converter/
├── index.html          # HTML structure
├── style.css           # CSS styling and animations
├── app.js              # JavaScript logic
└── README.md           # Project documentation
```

## How to Use 🚀

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Arslan7932/Currency-Converter.git
   cd Currency-Converter
   ```

2. **Open in Browser**
   - Simply open `index.html` in your web browser
   - No installation or build process required

3. **Convert Currency**
   - Enter the amount you want to convert
   - Select the "from" currency (default: USD)
   - Select the "to" currency (default: INR)
   - Click the "Get Exchange Rate" button to see the conversion
   - Use the swap button (↔) to quickly exchange the currencies

## Key Components 🔧

### app.js
- `updateExchangeRate()`: Fetches and calculates the exchange rate
- `updateFlag()`: Updates the flag image based on selected currency
- `swapCurrencies`: Swaps the "from" and "to" currencies with animation
- Currency dropdown population with all available currencies
- Event listeners for user interactions

### style.css
- Gradient background (purple to blue)
- Glassmorphism effect on the container
- Smooth transitions and hover effects
- Animation for swap button rotation
- Responsive media queries for mobile devices

## Supported Currencies 🌍

The application supports all major world currencies including:
- USD, EUR, GBP, JPY, INR, CAD, AUD, CHF, CNY, and many more

## Browser Compatibility 🌐

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Known Limitations ⚠️

- Requires internet connection to fetch exchange rates
- API rate limits may apply for high-frequency requests
- Historical exchange rates are not available (only current rates)

## Future Enhancements 🎯

- Add exchange rate history charts
- Implement caching for offline functionality
- Add cryptocurrency support
- Multiple currency conversion in one view
- Dark mode toggle
- Save favorite currency pairs

## License 📄

This project is open source and available under the MIT License.

## Contributing 🤝

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## Author 👨‍💻

Created by [Arslan7932](https://github.com/Arslan7932)

## Acknowledgments 🙏

- API data provided by [fawazahmed0](https://github.com/fawazahmed0/currency-api)
- Flag images from [Flags API](https://flagsapi.com/)
- Icons from Font Awesome

---

**Enjoy converting currencies! 🚀**
