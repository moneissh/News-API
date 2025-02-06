# News Aggregator

## Overview

The News Aggregator is a React-based web application that fetches and displays news articles by country using the MediaStack API. Users can select a country from a dropdown menu to view relevant news articles.

## Features

- Fetches news articles based on the selected country.
- Displays article title, description, published date, and an image (if available).
- Provides a "Read More" link to open the full article.
- Users can share news articles using the browser's share feature.
- Error handling for API failures and empty responses.

## Technologies Used

- React.js
- HTML, CSS
- MediaStack API

## Installation

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- npm (Node Package Manager) or yarn

### Steps to Install and Run

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/news-aggregator.git
   cd news-aggregator
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```
4. Open the app in your browser:
   ```sh
   http://localhost:5173/
   ```

## Configuration

### API Key Setup

The app requires an API key from MediaStack. Replace the `accessKey` value in the `fetchNewsByCountry` function in `StateWiseNewsAggregator.js` with your own API key:

```javascript
const accessKey = "your_api_key_here";
```

## Usage

1. Select a country from the dropdown menu.
2. View the latest news articles.
3. Click "Read More" to visit the source website.
4. Use the "Share" button to share the article link.

## Troubleshooting

- If no articles appear, ensure your API key is valid and has the necessary permissions.
- Check the browser console for any errors.
- Ensure you are connected to the internet.

## License

This project is licensed under the MIT License.

## Author

- **Your Name** - [Your GitHub Profile](https://github.com/yourusername)
