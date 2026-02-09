# 🎵 Unique Spotify Clone - Music Streaming Platform

A modern, uniquely-designed music streaming platform built with a contemporary tech stack. This project features a distinct user interface that sets it apart from traditional music streaming services.

## 🎨 Project Vision

This is not just a Spotify copy—we're building a music streaming platform with:
- **Unique UI/UX**: Modern, minimalist design with dark theme and vibrant accents
- **Smooth Animations**: Fluid transitions and interactive elements
- **Personalized Experience**: Smart playlists and recommendations
- **Community Features**: Share, discover, and collaborate with other music lovers

## 🛠 Tech Stack

### Frontend
- **React 18** - Modern UI library
- **React Router** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **Axios** - HTTP client for API calls

### Backend
- **Node.js & Express** - Server framework
- **MongoDB** - NoSQL database
- **JWT** - Authentication
- **Multer** - File uploads for music/album art

## 📁 Project Structure

```
spotify-clone/
├── frontend/              # React frontend application
│   ├── src/
│   │   ├── pages/        # Page components
│   │   ├── components/   # Reusable components
│   │   ├── styles/       # CSS/Tailwind styles
│   │   ├── services/     # API services
│   │   ├── App.jsx
│   │   └── index.js
│   ├── public/
│   └── package.json
├── backend/               # Express backend API
│   ├── src/
│   │   ├── routes/       # API routes
│   │   ├── models/       # Database models
│   │   ├── controllers/  # Business logic
│   │   ├── middleware/   # Custom middleware
│   │   └── server.js
│   ├── .env.example
│   └── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jaiprakash9257/spotify-clone.git
   cd spotify-clone
   ```

2. **Backend Setup**
   ```bash
   cd backend
   npm install
   cp .env.example .env
   # Edit .env with your MongoDB URI and JWT secret
   npm run dev
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm start
   ```

The frontend will run on `http://localhost:3000` and backend on `http://localhost:5000`

## 🎯 Core Features

### Phase 1 (MVP)
- [ ] User Authentication (Sign up, Login, Logout)
- [ ] Browse Music Library
- [ ] Create & Manage Playlists
- [ ] Music Player with Controls
- [ ] Search Functionality
- [ ] Unique UI Theme

### Phase 2
- [ ] User Profiles & Following
- [ ] Recommendations Engine
- [ ] Social Features (Sharing, Comments)
- [ ] Advanced Search & Filters

### Phase 3
- [ ] Mobile Responsive Design
- [ ] Offline Mode
- [ ] Premium Features
- [ ] Analytics Dashboard

## 🎨 UI/UX Inspiration

Our design philosophy:
- Clean, modern aesthetic with dark background
- Vibrant gradient accents (blues, purples, greens)
- Smooth, intuitive interactions
- Accessibility-first approach
- Mobile-responsive from the ground up

## 📝 API Endpoints

### Authentication
- `POST /api/auth/signup` - Register new user
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout

### Music
- `GET /api/music` - Get all tracks
- `GET /api/music/:id` - Get track details
- `GET /api/music/search` - Search tracks

### Playlists
- `GET /api/playlist` - Get user playlists
- `POST /api/playlist` - Create new playlist
- `PUT /api/playlist/:id` - Update playlist
- `DELETE /api/playlist/:id` - Delete playlist

### User
- `GET /api/user/profile` - Get user profile
- `PUT /api/user/profile` - Update profile

## 🧪 Testing

```bash
# Backend tests
cd backend && npm test

# Frontend tests
cd frontend && npm test
```

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🎵 Let's Build Something Amazing!

Join us in creating the next generation of music streaming platforms with a unique, user-centric design.

---

**Last Updated**: 2026-02-09 09:50:21