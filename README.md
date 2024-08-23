<img width="1466" alt="Screenshot 2024-08-23 at 10 27 16 AM" src="https://github.com/user-attachments/assets/aa8d9121-b12f-45cb-951c-b0e97fcbdf6d">


# Random Quote Generator

## Overview

The Random Quote Generator is a simple React application that displays a random quote from a collection of quotes. Each quote is displayed along with its author, and users can generate a new quote with a single click.


## Features

- **Random Quotes:** Displays a random quote from a predefined list.
- **Twitter:** Link to Twitter that automatically fills a post with the quote generated; user can post.


## Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/GavinWang-2024/Random-Quote-Generator.git
   cd random-quote-generator

2. **Install dependencies:**
Ensure Node.js installed, then run:

```
npm install
```

Start the development server:
```
npm run dev
```

## Usage

-Click the "New Quote" button to generate a random quote.
-The quote text and author will update dynamically.
-Tweet the Quote with the Twitter button


## Project Structure
src/
  -App.tsx: The main component that handles the UI and logic for displaying quotes.
  -main.tsx: Entry point for the React application.
  -quotes.json: The JSON file containing an array of quotes with their corresponding authors.

  
JSON Structure
The quotes.json file contains the list of quotes. Each quote is an object with the following structure:

```
{
  "quotes": [
    {
      "quote": "Your quote here",
      "author": "Author Name"
    },
    ...
  ]
}
```
