
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

## Deployment on Replit

### Quick Deploy

1. Import to Replit:
   - Go to [replit.com](https://replit.com)
   - Click "Create Repl"
   - Select "Import from GitHub"
   - Enter: `https://github.com/teamapexofc/Simpleportofolio/`

2. Click "Import from GitHub"

3. The Repl will automatically:
   - Install dependencies
   - Configure the environment
   - Be ready to run with the Run button

### Running on Replit

- Click the **Run** button at the top
- Your site will be live at the Replit-provided URL
- The site automatically uses port 5000 which is configured for production

### Replit Deployment

To deploy your portfolio to production on Replit:

1. Click on the "Deploy" tab in your Repl
2. Click "Deploy" to publish your site
3. Your portfolio will be live with a public URL

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
- **Main Site**: Your Replit deployment URL
- **Download Source**: `your-replit-url/download`

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

Built with ❤️ by ApeX Development using React, TypeScript, and Replit
