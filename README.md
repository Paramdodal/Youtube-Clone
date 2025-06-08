# YouTube Clone

A modern YouTube clone built with React and Tailwind CSS. This project mimics the core functionalities of YouTube, including video playback.

## 🛠 Tech Stack

- **React.js** - Frontend library
- **Tailwind CSS** - Utility-first CSS framework
- **Redux / Redux Toolkit** - State management
- **React Router** - Client-side routing
- **Axios** - HTTP requests
- **YouTube Data API v3** - For fetching video content
- **Vite / CRA** - (Update based on your setup)
- **Custom Hooks** - Reusable logic
- **.env** - Environment config for API keys

## 📁 Project Structure

src/
├── components/ # Reusable UI components
├── features/ # App features like video player, sidebar
├── hooks/ # Custom React hooks
├── pages/ # Page components (Home, Search, VideoDetail)
├── store/ # Redux store setup and slices
├── utils/ # Utility functions
├── App.js # Main app component
├── index.js # React entry point
├── index.css # Global styles

php
Copy
Edit

## ⚙️ Getting Started

### Prerequisites

- Node.js and npm installed
- YouTube Data API key from Google Cloud Console

### Installation

```bash
cd youtube-clone
npm install
```
Environment Variables
Create a .env file in the root directory and add your YouTube API key:
```bash
REACT_APP_YOUTUBE_API_KEY=your_api_key_here
```
Run the App
```bash
npm start
```
📸 Features
Video browsing and playback
Responsive layout using Tailwind CSS

📦 Available Scripts
npm start — Runs the app in development mode

npm run build — Builds the app for production

### Preview Video

Inspired by YouTube UI and built for educational purposes.
