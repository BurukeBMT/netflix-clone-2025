# 🎬 Netflix Clone 2025

A fully responsive Netflix clone built with React, featuring dynamic movie data from The Movie Database (TMDB) API. This project replicates the Netflix user interface with interactive features like movie trailers, categorized rows, and a sleek design.

## 🌟 Live Demo

🚀 **Deployed on Netlify:** [https://bmt-nf-dep.netlify.app/](https://bmt-nf-dep.netlify.app/)

📂 **GitHub Repository:** [https://github.com/BurukeBMT/netflix-clone-2025](https://github.com/BurukeBMT/netflix-clone-2025)

## ✨ Features

- **🎥 Dynamic Banner**: Random Netflix original movie with backdrop, title, description, and play buttons
- **📺 Movie Rows**: Categorized sections including Netflix Originals, Trending, Top Rated, Action, Comedy, Horror, Romance, TV Shows, and Documentaries
- **🎞️ Trailer Playback**: Click on any movie poster to watch the official trailer via YouTube integration
- **🔍 Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **🎨 Netflix UI**: Authentic Netflix-inspired design with smooth scrolling and hover effects
- **⚡ Fast Loading**: Optimized with React and efficient API calls
- **🔒 Secure API**: Uses TMDB API with environment variable protection

## 🛠️ Tech Stack

- **Frontend**: React 19.1.1
- **Styling**: CSS3 with custom components
- **Icons**: Material-UI Icons
- **API**: The Movie Database (TMDB)
- **HTTP Client**: Axios
- **Video Integration**: React YouTube & Movie Trailer
- **Build Tool**: Create React App
- **Deployment**: Netlify (connected to GitHub)

## 📁 Project Structure

```
netflix-clone-2025/
├── public/
│   ├── favicon.ico          # Netflix favicon
│   ├── index.html           # Main HTML template
│   ├── manifest.json        # PWA manifest
│   └── robots.txt           # SEO robots file
├── src/
│   ├── components/
│   │   ├── Banner/          # Hero banner component
│   │   ├── Footer/          # Footer with social links
│   │   ├── Header/          # Navigation header
│   │   └── Row/             # Movie rows and lists
│   ├── pages/
│   │   └── Home/            # Main home page
│   ├── utils/
│   │   ├── axios.jsx        # API configuration
│   │   └── requests.jsx     # TMDB API endpoints
│   ├── assets/              # Images and media
│   ├── App.jsx              # Main app component
│   └── index.jsx            # App entry point
├── netlify.toml             # Netlify deployment config
├── package.json             # Dependencies and scripts
└── README.md                # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- TMDB API Key (get one from [https://www.themoviedb.org/settings/api](https://www.themoviedb.org/settings/api))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/BurukeBMT/netflix-clone-2025.git
   cd netflix-clone-2025
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory:
   ```env
   REACT_APP_API_KEY=your_tmdb_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## 📜 Available Scripts

- `npm start` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm run eject` - Ejects from Create React App (irreversible)

## 🎯 Key Components

### Header Component
- Netflix logo navigation
- Menu items: Home, TV Shows, Movies, Latest, My List, Browse by Language
- Search, Notifications, and Account icons

### Banner Component
- Dynamic background from random Netflix original
- Movie title and description
- Play and My List buttons

### Row Components
- Horizontal scrolling movie lists
- Clickable posters that launch trailers
- Large row for Netflix Originals

### Footer Component
- Social media icons (Facebook, Instagram, YouTube)
- Legal and help links
- Service code and copyright notice

## 🔧 API Integration

The app uses The Movie Database (TMDB) API to fetch:
- Netflix Originals
- Trending content
- Top-rated movies
- Genre-specific movies (Action, Comedy, Horror, Romance)
- TV Shows
- Documentaries

## 🌐 Deployment

This project is automatically deployed to Netlify via GitHub integration. Any push to the main branch triggers a new build and deployment.

### Netlify Configuration
- Build command: `npm run build`
- Publish directory: `build`
- Connected repository: [https://github.com/BurukeBMT/netflix-clone-2025](https://github.com/BurukeBMT/netflix-clone-2025)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is for educational purposes only and is not affiliated with Netflix.

## 🙏 Acknowledgments

- Netflix for the inspiration
- The Movie Database (TMDB) for the API
- React community for the amazing framework
- Material-UI for the icons

---

**Built with ❤️ by Buruke BMT**
