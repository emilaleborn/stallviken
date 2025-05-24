# Stallvikens Islandshästar

En modern webbplats för Stallvikens Islandshästar byggd med Astro.

## 🚀 Build Instructions

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/emilaleborn/stallviken.git
cd stallviken

# Install dependencies
npm install
```

### Development
```bash
# Start development server with hot reload
npm run dev

# The site will be available at http://localhost:4321
```

### Building for Production
```bash
# Build the static site
npm run build

# Preview the production build locally
npm run preview
```

### Continuous Build (Watch Mode)
For continuous building during development:
```bash
# Watch for changes and rebuild automatically
npm run build -- --watch

# Or use the dev server which includes HMR (recommended)
npm run dev
```

### Deployment
The built site will be in the `dist/` folder and can be deployed to any static hosting service:
- Netlify
- Vercel  
- GitHub Pages
- Any web server

## 📁 Project Structure

```
/
├── src/
│   ├── layouts/      # Reusable page layouts
│   ├── pages/        # Astro pages (.astro files)
│   ├── styles/       # Global CSS styles
│   └── scripts/      # JavaScript files
├── images/           # Image assets
├── dist/            # Production build output
└── package.json     # Project dependencies
```

## 📄 Pages

### 🏠 Hem (index.astro)
- Kort presentation av Stallvikens Islandshästar
- Välkomsthälsning och bildspel (gården, hästar, träningar)
- Kort översikt av vad man hittar på hemsidan
- Snabblänkar till aktuella nyheter, kommande kurser och till salu-sidan

### 🐴 Utbildning & träning (utbildning.astro)
- Ridlektioner (privat, grupp)
- Hästträning (inridning, vidareutbildning)
- Kurser och helgträningar
- Tölt- och gångartsträning
- Målgrupper: nybörjare, erfarna, barn, vuxna
- Priser och bokning
- Bilder och omdömen från deltagare



### ℹ️ Om oss (om-oss.astro)
- Stallens historia
- Presentation av instruktör/ägare (bakgrund, filosofi)
- Om gården och dess läge
- Presentation av hästarna på gården (ej till salu)
- Värdegrund, säkerhet, djurvälfärd



### 📞 Kontakt (kontakt.astro)
- Kontaktformulär
- Telefonnummer och e-post
- Adress och vägbeskrivning
- Karta (Google Maps)
- Länkar till sociala medier



### 🐎 Hästar till salu (till-salu.astro)
- Aktuella hästar som är till salu
- Namn, ålder, kön, gångarter, personlighet, utbildningsnivå
- Foton och/eller videor
- Pris eller kontakt för pris
- Tidigare sålda hästar (valfritt – som referens)
- Köpvillkor och visning



### ~~📰 Blogg / Nyheter~~ (Removed)



### 📸 Bildgalleri (galleri.astro)
- Kategorier: Träning, Kurser, Vardag på gården, Hästar, Natur
- Möjlighet att förstora bilder
- (Eventuellt bildtext för varje bild)

## 🔧 Development

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run astro` - Run Astro CLI commands

### Technologies Used
- [Astro](https://astro.build) - Static Site Generator
- Vanilla JavaScript
- CSS3 with CSS Variables
- Google Fonts (Playfair Display & Open Sans)

## 📧 Contact
For questions about the website, contact: info@stallviken.se



