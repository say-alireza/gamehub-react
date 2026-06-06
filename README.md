
# Game Shop - React Project

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![RAWG API](https://img.shields.io/badge/RAWG_API-000?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Yes-brightgreen?style=for-the-badge)

A modern game shop website built with React, powered by RAWG.io's API.

![Preview](https://github.com/user-attachments/assets/8c3a853c-e467-468a-9067-b6b5bf2f7ace)

## ✨ Features

- 🔍 **Game Search** - Find games by title, genre, or platform
- 🎮 **Detailed Game Pages** - View descriptions, ratings, screenshots, and more
- 📱 **Fully Responsive** - Works on desktop, tablet, and mobile
- ⚡ **Fast Loading** - Optimized API calls and lazy loading
- 🌓 **Dark/Light Mode** - (Optional - add if implemented)

## 🛠 Technologies Used

- **Frontend**: React.js, React Router
- **Styling**: Chakra UI
- **API**: RAWG Video Games Database API
- **State Management**: Context API / Redux (if used)
- **HTTP Client**: Axios

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)
- npm 
- RAWG API key (free tier available)
 ## 🛠 Installation
1. Clone the repository: `git clone https://github.com/your-username/game-shop.git`
2. Navigate to project: `cd game-shop`
3. Install dependencies: `npm install` or `yarn install`
4. Create `.env` file and add your API key: `REACT_APP_RAWG_API_KEY=your_api_key_here`
5. Start development server: `npm start` or `yarn start`
6. Open in browser: [http://localhost:3000](http://localhost:3000)


## 🔧 Project Structure
```
game-shop/
├── public/          # Static files
├── src/
│   ├── components/  # Reusable components
│   ├── pages/       # Page components
│   ├── hooks/       # Custom hooks
│   ├── context/     # Context providers (if used)
│   ├── styles/      # CSS files
│   ├── utils/       # Utility functions
│   ├── App.js       # Main app component
│   └── index.js     # Entry point
├── .env.example     # Environment variables template
└── package.json     # Project dependencies
```
## 🌱 Future Improvements
Add user authentication

Implement shopping cart functionality

Add game trailers section

Include user reviews system

## 🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request
