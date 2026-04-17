# Elias Luzwehimana - Software Engineer Portfolio

A modern, minimalist portfolio website showcasing software engineering projects, skills, and experience.

## 📋 Features

- Responsive design with modern glassmorphism UI
- Smooth animations and transitions
- Custom cursor interactions
- Mobile-optimized layout
- Educational background showcase
- Project showcase
- Contact information

## 🚀 Deployment on Vercel

This is a static HTML site that deploys seamlessly on Vercel.

### Prerequisites

- Git installed
- GitHub account
- Vercel account (free tier available at [vercel.com](https://vercel.com))

### Steps to Deploy

1. **Push to GitHub** (already done or do it now):
   ```bash
   git add .
   git commit -m "Add Vercel configuration"
   git push origin main
   ```

2. **Deploy on Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will automatically detect the static site
   - Click "Deploy"

3. **Custom Domain** (optional):
   - In Vercel dashboard, go to Settings > Domains
   - Add your custom domain

## 🛠️ Local Development

To run locally:

```bash
npx http-server
```

Then open `http://localhost:8080` in your browser.

Or use the npm script:

```bash
npm run preview
```

## 📁 Project Structure

```
elias-portfolio/
├── index.html          # Main portfolio page
├── package.json        # Project metadata
├── vercel.json         # Vercel configuration
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 🎨 Customization

All styles are inline in `index.html`. To modify:

- **Colors**: Edit the CSS variables in the `:root` selector
- **Content**: Update the HTML sections (Hero, About, Education, Projects, Contact)
- **Fonts**: Modify the Google Fonts links in the `<head>`

## 📞 Contact

- Email: eliasnhunzwe@gmail.com
- Phone: +46 72 775 91 88
- Location: Stockholm, Sweden

## 📄 License

MIT License - feel free to use this as a template for your own portfolio.
