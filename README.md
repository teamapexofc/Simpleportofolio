# Portfolio - Open Source

A modern, full-stack portfolio website built with React, TypeScript, Express, and Tailwind CSS.

## Features

- 🎨 Modern UI with dark mode support
- ⚡ Fast development with Vite
- 🎯 Type-safe with TypeScript
- 🎨 Beautiful components with shadcn/ui
- 📱 Fully responsive design
- 📦 Easy deployment to Replit

## Tech Stack

### Frontend
- React 19
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui components
- Wouter (routing)
- TanStack Query
- Framer Motion (animations)

### Backend
- Node.js
- Express
- TypeScript

## Getting Started

### Prerequisites
- Node.js 20.x or higher
- npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/teamapexofc/Simpleportofolio/
cd Simpleportofolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at:
- Frontend: http://localhost:5000
- Backend API: http://localhost:5000/api

### Available Scripts

- `npm run dev` - Start development server (both frontend and backend)
- `npm run dev:client` - Start only the frontend development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run check` - Type check with TypeScript

## Project Structure

```
├── client/                 # Frontend application
│   ├── src/
│   │   ├── components/    # React components
│   │   │   └── ui/       # Reusable UI components (shadcn/ui)
│   │   ├── pages/        # Page components
│   │   ├── hooks/        # Custom React hooks
│   │   ├── lib/          # Utility functions
│   │   └── index.css     # Global styles
│   └── index.html        # HTML template
├── server/               # Backend application
│   ├── app.ts           # Express app setup
│   ├── routes.ts        # API routes
│   ├── index-dev.ts     # Development server
│   └── index-prod.ts    # Production server
├── shared/              # Shared types and schemas
└── attached_assets/     # Static assets (images, etc.)
```

## Key Features Explained

### Download Source Code
Visit `/download` to download the complete portfolio source code as a ZIP file.

### Responsive Design
Built with mobile-first approach using Tailwind CSS breakpoints.

### Animated Components
Smooth animations powered by Framer Motion for an engaging user experience.

## Deployment

### Deploy on Vercel

The easiest way to deploy this portfolio is using [Vercel](https://vercel.com):

1. Push your code to a GitHub repository
2. Visit [vercel.com](https://vercel.com) and sign in
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect the framework and configure:
   - Build Command: `npm run build`
   - Output Directory: `dist/public`
   - Install Command: `npm install`
6. Click "Deploy"
7. Your portfolio will be live at `<your-project>.vercel.app`

You can also connect a custom domain in the Vercel project settings.

### Local Development

To run the development server locally:

```bash
npm run dev
```

The application will be available at http://localhost:5000

## Customization

### Branding
- Update meta tags in `client/index.html`
- Replace favicon in `client/public/`
- Update content in components (Hero, About, Contact, etc.)

### Styling
- Modify `client/src/index.css` for global styles
- Update Tailwind configuration as needed
- Customize shadcn/ui components in `client/src/components/ui/`

### Content Updates
- **Hero Section**: Edit `client/src/components/Hero.tsx`
- **About Section**: Edit `client/src/components/About.tsx`
- **Projects**: Edit `client/src/components/Projects.tsx`
- **Contact Info**: Edit `client/src/components/Contact.tsx`
- **Footer Links**: Edit `client/src/components/Footer.tsx`

### API Routes
- Add new routes in `server/routes.ts`
- Backend runs on the same domain in production

## Important URLs

After deployment, your portfolio will have:
- **Main Site**: `https://<your-project>.vercel.app` (or your custom domain)
- **Download Source**: `https://<your-project>.vercel.app/download`

## Technologies Used

- **React 19** - Modern UI library
- **TypeScript** - Type-safe development
- **Vite** - Fast build tool
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn/ui** - High-quality UI components
- **Framer Motion** - Animation library
- **Express** - Backend server
- **Wouter** - Lightweight routing

## License

MIT - Feel free to use this portfolio template for your own projects!

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## Support

For issues or questions:
- Open an issue on [GitHub](https://github.com/teamapexofc/Simpleportofolio/issues)
- Check existing issues for solutions

---

Built with ❤️ by [ApeX Development](https://github.com/teamapexofc) using React and TypeScript
