# bibleversion

A modern, responsive Bible reading application built with React that provides access to multiple Bible translations in various languages. Designed for an enhanced scripture study and reading experience.

## Features

- **Multiple Translations** - Access various Bible translations across different languages
- **Language Support** - Read scripture in your preferred language
- **Theme Switcher** - Toggle between dark and light mode with `localStorage` persistence
- **Adjustable Font Size** - Customize the reading font size from 10pt to 30pt
- **Persistent Reading Position** - Saves your last selected book and chapter via `localStorage`
- **Smooth Navigation** - Browse books and chapters with animated transitions and prev/next controls
- **Responsive Design** - Mobile-first layout optimized for all screen sizes
- **Modular Architecture** - Custom hooks, contexts, and separated page components

## Tech Stack

- **Framework**: [Create React App](https://create-react-app.dev)
- **Library**: React 19
- **Routing**: React Router 7
- **UI Components**: Material UI 7
- **API**: [Scripture API (api.bible)](https://scripture.api.bible)

## Prerequisites

- Node.js 14.x or higher
- npm or yarn

## Installation

1. Clone the repository

```bash
git clone https://github.com/andrejkoller/bibleversion.git
cd bibleversion
```

2. Install dependencies

```bash
npm install
```

3. Create a `.env.local` file in the root directory and add your Scripture API credentials

```env
REACT_APP_BASE_URL="/api/v1"
REACT_APP_API_KEY="your-api-key-here"
```

4. Run the development server

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## API Key

This application uses the [Scripture API](https://scripture.api.bible/). To get your free API key:

1. Visit [https://scripture.api.bible/](https://scripture.api.bible/)
2. Sign up for a free account
3. Generate your API key
4. Add it to your `.env.local` file

## Project Structure

```
bibleversion/
├── public/
│   ├── index.html
│   ├── fonts/
│   ├── icons/
│   └── images/
├── src/
│   ├── components/
│   │   ├── footer/
│   │   ├── header/
│   │   └── pages/
│   │       ├── about/
│   │       ├── bible/
│   │       │   ├── chapter/
│   │       │   └── translations/
│   │       ├── developers/
│   │       ├── help/
│   │       ├── home/
│   │       ├── more/
│   │       ├── search/
│   │       ├── settings/
│   │       │   ├── font-size/
│   │       │   ├── language/
│   │       │   └── theme/
│   │       └── translation-language/
│   ├── configs/                      # Navigation and settings configuration
│   ├── contexts/                     # React context providers
│   ├── hooks/                        # Custom React hooks
│   ├── lib/utils/                    # Utility functions
│   ├── services/
│   │   └── bible-service.js          # Scripture API integration
│   ├── App.js
│   └── index.js
├── .env.local                        # Local environment variables
├── .env.production                   # Production environment variables
├── package.json
├── LICENSE
└── SECURITY.md
```

## Screenshots

![Screenshot 1](public/images/screenshot-1.png)
![Screenshot 2](public/images/screenshot-2.png)
![Screenshot 3](public/images/screenshot-3.png)
![Screenshot 4](public/images/screenshot-4.png)
![Screenshot 5](public/images/screenshot-5.png)
![Screenshot 6](public/images/screenshot-6.png)
![Screenshot 7](public/images/screenshot-7.png)
![Screenshot 8](public/images/screenshot-8.png)
![Screenshot 9](public/images/screenshot-9.png)
![Screenshot 10](public/images/screenshot-10.png)
![Screenshot 11](public/images/screenshot-11.png)
![Screenshot 12](public/images/screenshot-12.png)
![Screenshot 13](public/images/screenshot-13.png)
![Screenshot 14](public/images/screenshot-14.png)
![Screenshot 15](public/images/screenshot-15.png)
![Screenshot 16](public/images/screenshot-16.png)
![Screenshot 17](public/images/screenshot-17.png)
![Screenshot 18](public/images/screenshot-18.png)
![Screenshot 19](public/images/screenshot-19.png)
![Screenshot 20](public/images/screenshot-20.png)
![Screenshot 21](public/images/screenshot-21.png)
![Screenshot 22](public/images/screenshot-22.png)
![Screenshot 23](public/images/screenshot-23.png)
![Screenshot 24](public/images/screenshot-24.png)
![Screenshot 25](public/images/screenshot-25.png)
![Screenshot 26](public/images/screenshot-26.png)

## License

This project is licensed under the [MIT License](LICENSE).
