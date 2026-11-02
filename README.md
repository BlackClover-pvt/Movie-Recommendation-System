# 🎬 Movie Recommendation System

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%20%7C%203.9%20%7C%203.10%20%7C%203.11-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Flask-REST%20API-000000?style=flat&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/React-19.0-61DAFB?style=flat&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/scikit--learn-TF--IDF%20%26%20Cosine%20Sim-F7931E?style=flat&logo=scikit-learn&logoColor=white" alt="scikit-learn" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Material--UI-UI%20Components-007FFF?style=flat&logo=mui&logoColor=white" alt="Material-UI" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=flat&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/License-MIT-brightgreen?style=flat" alt="MIT License" />
</p>

<p align="center">
  <strong>An intelligent movie recommendation system for personalized mood-based suggestions, rating-based filtering, and conversational movie discovery powered by React, Flask, and scikit-learn.</strong>
</p>

<p align="center">
  Developed by <strong>BlackClover</strong> (Aritra Chowdhury, Kaustav Saha)
  <br />
  <a href="mailto:blackclover.rick@gmail.com">
    <img src="https://img.shields.io/badge/Email-blackclover.rick%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## 📌 Table of Contents

---

- [Overview](#overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
  - [Frontend](#frontend)
  - [Backend](#backend)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Configuration](#configuration)
  - [Backend Configuration](#backend-configuration)
  - [Frontend Configuration](#frontend-configuration)
- [API Endpoints](#api-endpoints)
- [Design Features](#design-features)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Authors](#authors)

---

<a id="overview"></a>
## 📖 Overview

The **Movie Recommendation System** is a modern, interactive web application that helps users discover movies based on their mood, preferences, and ratings. Built with a responsive **React.js** frontend and a lightweight **Python Flask** backend, the system leverages TF-IDF vectorization and cosine similarity to deliver tailored movie suggestions alongside interactive conversational mood detection.

---

<a id="key-features"></a>
## 🌟 Key Features

- **Smart Movie Recommendations**
  - Mood-based recommendations
  - Genre-based filtering
  - Rating-based suggestions
  - Popular movies showcase

- **Interactive Chatbot**
  - Natural language processing for mood detection
  - Genre recognition
  - Conversational interface
  - Real-time responses

- **Modern UI/UX**
  - Responsive design
  - Dark theme with neon accents
  - Glass-morphism effects
  - Smooth animations
  - Star rating system

- **Search Functionality**
  - Real-time search
  - Pagination
  - Genre filtering
  - Rating filtering

---

<a id="tech-stack"></a>
## 🛠️ Tech Stack

### <a id="frontend"></a>Frontend
- React.js
- Material-UI
- Axios
- Custom CSS with modern design principles

### <a id="backend"></a>Backend
- Python Flask
- Pandas
- NumPy
- scikit-learn

---

<a id="project-structure"></a>
## 📁 Project Structure

```
movie_recommendation_2/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Chatbot.js
│   │   │   ├── MovieCard.js
│   │   │   └── RatingStars.js
│   │   ├── styles/
│   │   │   ├── fonts.css
│   │   │   └── theme.css
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── backend/
│   ├── app.py
│   ├── data/
│   │   ├── movies.csv
│   │   └── ratings.csv
│   └── requirements.txt
└── README.md
```

---

<a id="getting-started"></a>
## 🚀 Getting Started

### <a id="prerequisites"></a>Prerequisites
- Python 3.8+
- Node.js 14+
- npm or yarn

### <a id="installation"></a>Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
```

2. Set up the backend
```bash
cd backend
pip install -r requirements.txt
python app.py
```

3. Set up the frontend
```bash
cd frontend
npm install
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

---

<a id="configuration"></a>
## 🔧 Configuration

### <a id="backend-configuration"></a>Backend Configuration
- The backend server runs on `http://localhost:5000`
- API endpoints are prefixed with `/api/`
- CORS is enabled for all origins

### <a id="frontend-configuration"></a>Frontend Configuration
- The frontend development server runs on `http://localhost:3000`
- API calls are configured to connect to the backend server

---

<a id="api-endpoints"></a>
## 📝 API Endpoints

- `GET /api/movies` - Get all movies with pagination
- `GET /api/search` - Search movies by title
- `POST /api/recommendations/mood` - Get mood-based recommendations
- `POST /api/recommendations/rating` - Get rating-based recommendations

---

<a id="design-features"></a>
## 🎨 Design Features

- **Color Scheme**
  - Neon Purple (#9333EA)
  - Neon Pink (#EC4899)
  - Neon Blue (#3B82F6)
  - Neon Cyan (#06B6D4)
  - Dark Background (#0a0a1a)

- **Typography**
  - Headings: Orbitron
  - Body: Space Grotesk
  - Accent: Rajdhani

- **Effects**
  - Glass-morphism
  - Neon glow effects
  - Smooth transitions
  - Hover animations

---

<a id="contributing"></a>
## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<a id="license"></a>
## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<a id="acknowledgments"></a>
## 🙏 Acknowledgments

- MovieLens dataset for providing the movie data
- Material-UI for the component library
- Google Fonts for the typography

---

<a id="authors"></a>
## 👥 Authors

Developed by **BlackClover** (Aritra Chowdhury, Kaustav Saha)

- ✉️ **Email**: [blackclover.rick@gmail.com](mailto:blackclover.rick@gmail.com)

