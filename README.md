# ServicePro Mobile - Frontend Demo

Mobile-optimized React application for ServicePro911 field service management.

## Features

- 50+ mobile-optimized pages
- Complete UI with mock data
- Mobile-first design with bottom navigation
- Red-orange color scheme
- Responsive layouts

## Local Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The app will be available at `http://localhost:8081`

## Deploy to Vercel

1. Push your code to GitHub
2. Import your repository in [Vercel](https://vercel.com)
3. Vercel will automatically detect Vite and configure:
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
   - **Install Command**: `npm install`

The `vercel.json` file is already configured for optimal deployment.

## Project Structure

```
mobile-version/
├── src/
│   ├── components/     # React components
│   ├── pages/         # Page components
│   ├── data/          # Mock data
│   └── lib/           # Utilities
├── public/            # Static assets
├── dist/              # Build output (generated)
└── package.json       # Dependencies
```

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Radix UI Components

