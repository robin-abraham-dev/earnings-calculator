# Business Partner Earnings Calculator

A modern, responsive web application for calculating monthly earnings from crypto trading partnerships. This calculator helps business partners estimate their revenue share based on client trading activity, leverage, and turnover.

## Features

- **4 Interactive Calculator Modules**: Compare different business scenarios side by side
- **Real-time Calculations**: Instant updates as you adjust parameters
- **Interactive Sliders**: Easy adjustment of leverage (1x-100x) and turnover (1-50 trades)
- **Dark Theme UI**: Modern, professional interface with glassmorphism effects
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Indian Currency Formatting**: Proper ₹ symbol and Indian number formatting

## Calculation Model

The calculator uses the following formula based on the provided Excel model:

1. **Total Capital** = Number of Clients × Average Capital per Client
2. **Effective Trading Capital** = Total Capital × Average Leverage Used
3. **Total Monthly Volume** = Effective Trading Capital × Trades per Client per Month
4. **Total Fees Charged** = Total Monthly Volume × Trading Fee (0.05%)
5. **Monthly Earnings** = Total Fees Charged × Partner Share (20%)

## Usage

1. Open `index.html` in your web browser
2. Enter the number of trading clients
3. Set the average capital per client
4. Adjust leverage using the slider (1x to 100x)
5. Set the number of trades per client per month
6. Click "Calculate Earnings" to see your monthly revenue

## Parameters

- **Trading Fee**: 0.05% (fixed)
- **Partner Share**: 20% (fixed)
- **Leverage Range**: 1x to 100x
- **Turnover Range**: 1 to 50 trades per month

## Deployment

This application is designed to be hosted on GitHub Pages:

1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your calculator will be available at `https://yourusername.github.io/Earnings-Calculator`

## Files Structure

```
├── index.html          # Main application file
├── README.md           # This documentation
├── LICENSE             # MIT License
└── .gitignore          # Git ignore file
```

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

MIT License - see LICENSE file for details.

## Contributing

Feel free to submit issues and enhancement requests!

---

**Note**: This calculator is for estimation purposes only. Actual earnings may vary based on market conditions and platform-specific terms.