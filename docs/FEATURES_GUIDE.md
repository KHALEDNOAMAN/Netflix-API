# Netflix Clone - Features Guide

## Features
| Feature | Description |
|---------|-------------|
| Movie Browsing | Browse by genre, trending, top rated |
| Search | Full-text search across movies/shows |
| Trailers | Play YouTube trailers inline |
| Watchlist | Save movies to watch later |
| Responsive | Works on mobile, tablet, desktop |

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React + TypeScript |
| API | TMDB API |
| Styling | Tailwind/CSS Modules |
| Auth | Firebase/NextAuth |

## API Endpoints
| Endpoint | Description |
|----------|-------------|
| /trending | Trending movies this week |
| /genre/{id} | Movies by genre |
| /search?q= | Search movies |
| /movie/{id} | Movie details |

## Setup
```bash
git clone https://github.com/mwakidenis/Netflix-API.git
cd Netflix-API
npm install
echo "TMDB_API_KEY=your_key" > .env
npm run dev
```