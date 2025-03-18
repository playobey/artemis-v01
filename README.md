# Artemis - Content Platform

Artemis is a modern web application built with Next.js, React, and TypeScript that showcases content creators and their videos.

## Features

- **Dark/Light Theme Support**: Toggle between dark and light modes for comfortable viewing.
- **Videos Page**: Browse and purchase premium content from creators.
- **Models Page**: Discover content creators and explore their profiles.
- **Chat System**: Message and interact with content creators.
- **User Profile**: Manage your account, subscriptions, and purchases.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop experiences.

## Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Theme Management**: next-themes

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/artemis.git
cd artemis
```

2. **Install dependencies**

```bash
npm install
```

3. **Run the development server**

```bash
npm run dev
```

4. **Open in browser**

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `src/app`: Route components for each page
- `src/components`: Reusable UI components
- `src/styles`: Global styles and Tailwind CSS configuration
- `src/types`: TypeScript type definitions

## Pages

- `/`: Home page
- `/videos`: Browse available videos
- `/models`: Discover content creators
- `/chat`: Message system for interacting with creators
- `/profile`: User profile management

## Deployment

Build the application for production:

```bash
npm run build
```

The optimized production build can be started with:

```bash
npm start
```

## License

MIT