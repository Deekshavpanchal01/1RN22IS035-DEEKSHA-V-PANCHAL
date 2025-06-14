# Stock Aggregator Frontend

This project is a React-based frontend application designed to aggregate and display stock prices. It fetches data from an external API and presents it in a user-friendly interface.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Services](#services)
- [Types](#types)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with the Stock Aggregator Frontend, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd stock-aggregator-frontend
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage

To run the application in development mode, use the following command:
```
npm start
```
This will start the development server and open the application in your default web browser.

## Components

- **StockList**: A component that fetches and displays a list of stock prices.
- **Home**: The main page of the application that includes the StockList component.

## Services

- **stockService**: Contains functions for fetching stock price data from an external API.

## Types

- TypeScript interfaces and types are defined in the `src/types/index.ts` file to ensure type safety throughout the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.