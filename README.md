[README.md](https://github.com/user-attachments/files/24333661/README.md)
# Caviar Records - Official Website

A luxurious, full-service music label website built with React, showcasing artist development, production services, marketing agency capabilities, and Caviar Studios.

## 🎵 About Caviar Records

Caviar Records is a full-service music label operating like Sony or Warner, offering:
- **Record Label** - Artist signing, development, release & distribution
- **Production Services** - Beats, mixing, mastering, audio engineering
- **Marketing Agency** - Brand campaigns, influencer partnerships (largest roster in MENA)
- **Caviar Studios** - Music videos, films, and visual content

## 🚀 Tech Stack

- **React 18.3** - UI framework
- **Vite 6.3** - Build tool & dev server
- **React Router 7.11** - Navigation & routing
- **Motion/React 12.23** - Smooth animations
- **Tailwind CSS 4.1** - Styling
- **Lucide React** - Icon library

## 📦 Installation

1. **Clone the repository:**
```bash
git clone https://github.com/YOUR_USERNAME/caviar-records.git
cd caviar-records
```

2. **Install dependencies:**
```bash
npm install
```

3. **Run development server:**
```bash
npm run dev
```

Your site will be running at `http://localhost:5173`

## 🏗️ Build for Production

```bash
npm run build
```

This creates an optimized production build in the `/dist` folder.

## 📤 Deployment Options

### Option 1: Vercel (Recommended - Easiest)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel auto-detects Vite settings
6. Click "Deploy"
7. Done! Your site is live with a free `.vercel.app` domain

**Custom Domain:** Add your domain in Vercel project settings

### Option 2: Netlify

1. Push your code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Connect to GitHub and select your repository
5. Build settings:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
6. Click "Deploy"

**Custom Domain:** Add your domain in Netlify site settings

### Option 3: GitHub Pages

1. Install gh-pages:
```bash
npm install --save-dev gh-pages
```

2. Add to `package.json`:
```json
{
  "homepage": "https://YOUR_USERNAME.github.io/caviar-records",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  }
}
```

3. Update `vite.config.ts`:
```javascript
export default defineConfig({
  base: '/caviar-records/',
  // ... rest of config
})
```

4. Deploy:
```bash
npm run deploy
```

## 📁 Project Structure

```
caviar-records/
├── src/
│   ├── app/
│   │   ├── App.tsx              # Main app with routing
│   │   └── components/
│   │       ├── HomePage.tsx     # Landing page
│   │       ├── RecordLabel.tsx  # Record label service
│   │       ├── ProductionServices.tsx
│   │       ├── MarketingAgency.tsx
│   │       ├── BrandsInfluencer.tsx
│   │       ├── CaviarStudios.tsx
│   │       ├── ServicesPage.tsx # Services overview
│   │       ├── Contact.tsx
│   │       ├── AboutUs.tsx
│   │       ├── Privacy.tsx
│   │       ├── Careers.tsx
│   │       ├── Navigation.tsx
│   │       ├── Footer.tsx
│   │       └── ...
│   └── styles/
│       ├── fonts.css
│       ├── theme.css
│       └── tailwind.css
├── public/
├── package.json
└── vite.config.ts
```

## 🎨 Design Features

- **Luxurious vintage aesthetic** - Beige/cream (#F5EFE0, #D4C5A5) colors
- **Elegant typography** - Bebas Neue + Playfair Display fonts
- **Smooth animations** - Motion/React with performance optimizations
- **Fully responsive** - Mobile, tablet, desktop
- **13 pages** - Complete website with all services
- **Consistent CTA pattern** - Black background sections above footer

## 🌐 Pages

1. Home Page (`/`)
2. Services Overview (`/services`)
3. Record Label (`/record-label`)
4. Production Services (`/production-services`)
5. Brands & Influencer (`/brands-influencer`)
6. Marketing Agency (`/marketing-agency`)
7. Caviar Studios (`/caviar-studios`)
8. Gallery - Coming Soon (`/gallery`)
9. Beats Marketplace - Coming Soon (`/beats`)
10. Contact (`/contact`)
11. About Us (`/about`)
12. Privacy Policy (`/privacy`)
13. Careers (`/careers`)

## 📞 Contact Information

- **Email:** Contact@caviarrecords.com
- **Phone:** +44 7365 540894
- **Address:** Office 6186, 182-184 High Street North, East Ham, London, E6 2JA

## 📝 License

© 2024 Caviar Records. All rights reserved.

## 🛠️ Development

Built with ❤️ using React + Vite

For support or questions, contact: Contact@caviarrecords.com
