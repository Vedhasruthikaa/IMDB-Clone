# Movieo - Movie Browsing Application

Movieo is a modern web application built with React that allows users to browse, search, and explore movies and TV shows. With a sleek user interface and comprehensive features, users can discover their next favorite entertainment content.

## Features

- **User Authentication**: Secure login system to access personalized features
- **Movie & TV Show Exploration**: Browse through popular movies and TV shows
- **Search Functionality**: Search for specific movies and TV shows
- **Wishlist**: Save your favorite content to a personal wishlist
- **Responsive Design**: Fully responsive interface that works on desktop and mobile devices
- **Video Playback**: Watch trailers and video content
- **Detailed Information**: Access comprehensive details about movies and TV shows

## Technology Stack

- **Frontend**: React.js
- **Styling**: Tailwind CSS
- **State Management**: Redux (movieoSlice)
- **Routing**: React Router
- **Icons**: React Icons
- **HTTP Client**: Axios

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository
```bash
git clone [repository-url]
cd movieoapp-main
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:3000`

### Login Credentials (Demo)

- Email: user@example.com
- Password: password123

## Project Structure

```
src/
├── assets/         # Static assets like images
├── components/     # Reusable React components
├── constants/      # Application constants
├── hooks/          # Custom React hooks
├── pages/          # Page components
├── routes/         # Routing configuration
├── store/          # Redux store setup
└── App.js          # Root component
```

## Features in Detail

### Home Page
- Banner showcasing featured content
- Horizontal scroll cards for different categories
- Quick access to popular content

### Explore Page
- Grid layout of movies/TV shows
- Infinite scroll functionality
- Filtering options

### Search
- Real-time search functionality
- Search results with movie/TV show cards
- Detailed view access

### User Features
- Personal wishlist management
- User profile dropdown
- Secure authentication

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
