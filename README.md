# Twimba

## Description

Twimba is a simple front-end web application that mimics the basic functionality of "Good Old Twitter." It allows users to view a feed of tweets, like and retweet posts, view replies, and create new tweets. All data is handled in-memory using mock data, with no backend or persistent storage. This project is built as a learning exercise, likely inspired by a Scrimba course.

## Features

- **Feed Display**: View a list of tweets with user handles, profile pictures, text, likes, retweets, and replies.
- **Interact with Tweets**:
  - Like/Unlike tweets (updates count and icon color).
  - Retweet/Unretweet tweets (updates count and icon color).
  - Toggle visibility of replies.
- **Post New Tweets**: Enter text in the input area and submit to add a new tweet to the top of the feed.
- **Responsive UI**: Basic styling for a Twitter-like interface using vanilla CSS.

## Technologies Used

- **Languages**: HTML, CSS, JavaScript (68.1% JS, 19.9% CSS, 12.0% HTML).
- **Build Tool**: Vite for fast development and building.
- **Dependencies**: UUID library for generating unique tweet IDs (imported via JSPM).
- **No Backend**: All logic is client-side; data is static and in-memory.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/SergKhlobystov/Twimba.git
   ```
2. Navigate to the project directory:
   ```
   cd Twimba
   ```
3. Install dependencies:
   ```
   npm install
   ```

## Usage

1. Start the development server:
   ```
   npm run dev
   ```
2. Open your browser and visit `http://localhost:5173` (or the port shown in the console).
3. Interact with the app:
   - Type in the textarea and click "Tweet" to post.
   - Click heart icons to like, arrow icons to retweet, or speech bubble to show/hide replies.

## Project Structure

```
Twimba/
├── images/              # Static images (e.g., profile pics, logos)
├── .gitattributes       # Git configuration
├── README.md            # This file
├── data.js              # Mock tweet data (array of tweet objects)
├── index.css            # Main stylesheet for UI
├── index.html           # Entry HTML file with basic structure
├── index.js             # Core JavaScript logic (event handling, rendering)
├── package.json         # NPM dependencies and scripts
└── vite.config.js       # Vite configuration
```

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements, such as adding more features or backend integration.

## License

This project is open-source and available under the MIT License (if not specified otherwise). For more details, check the repository.

- Inspired by [Scrimba](https://scrimba.com/) coding courses.
