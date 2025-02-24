# Dollar Cost Averaging (DCA) Calculator

A web-based calculator that helps investors track and calculate their average purchase price across multiple buy and sell transactions. Perfect for cryptocurrency and stock investments.
Available at https://populus.ddns.net/D.C.A/

## Features

- **Multiple Asset Support**: Track different assets (cryptocurrencies, stocks, etc.) separately
- **Flexible Input Options**:
  - Per Unit Price: Traditional price per share/coin input
  - Total Value: Enter the total transaction value instead of per-unit price
  - No Price: Track airdrops, mining rewards, or other zero-cost acquisitions
- **Advanced Calculation**:
  - Accurate DCA calculation considering both buys and sells
  - Prevents selling more units than available
  - Maintains correct cost basis after partial sells
- **High Precision**:
  - Supports up to 32 decimal places
  - Perfect for small cryptocurrency units
  - Handles scientific notation (e.g., 1.23e-8)
- **Data Management**:
  - Auto-saves all entries locally
  - Export/Import functionality for backup and sharing
  - Persistent storage across browser sessions

## Usage

1. **Adding Assets**:
   - Click "+ Add New Asset" to create a new asset tracker
   - Name your asset (e.g., "Bitcoin", "Tesla Stock")

2. **Adding Transactions**:
   - Choose operation type:
     - Per Unit Price: For regular trades
     - Total Value: When you know the total amount spent
     - No Price: For airdrops or mining rewards
   - Select Buy/Sell
   - Enter amount and price
   - Click "+ Add Entry" for more transactions

3. **Calculating Average**:
   - Click "Calculate Average" to see:
     - Current average price per unit
     - Net position (total units)
     - Total cost basis

4. **Data Management**:
   - Entries are automatically saved
   - Use Export/Import for backup or sharing

## Input Formats

- Supports both comma (,) and period (.) as decimal separators
- Scientific notation supported (e.g., "1.23e-8" = "0.0000000123")
- High precision calculations for small unit prices

## Browser Support

Works on modern browsers with local storage support:
- Chrome
- Firefox
- Safari
- Edge

## Installation

No installation required! This is a client-side application that runs entirely in your browser.

1. Download the `index.html` file
2. Open it in your web browser
3. Start tracking your investments!

## Privacy

All calculations and data storage happen locally in your browser. No data is sent to any server.

## Contributing

Feel free to submit issues and enhancement requests!

## License

MIT License - feel free to use and modify for your needs.

## Support the Development

If you find this tool useful, consider supporting the developer:
- Metamask (ERC-20/BSC): `0xaf8817fe4ec64888f8a4586cf6b1432058a80066` 
