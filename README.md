```markdown
# Martin Mutugi - Portfolio  
[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR_BADGE_ID/deploy-status)](https://martinmutugiportfolio.netlify.app/)  

## Features  
- Dark/Light Mode: CSS-powered theme switching (no JavaScript)  
- Responsive Design: Mobile-first layout with CSS Grid/Flexbox  
- Performance: 95+ Lighthouse score (optimized assets)  

## Built With  
| Area       | Technologies |  
|------------|--------------|  
| Structure  | Semantic HTML5 |  
| Styling    | CSS3 (Variables, Grid, Flexbox) |  
| Hosting    | Netlify |  

## Preview  
| Dark Mode | Light Mode |  
|-----------|------------|  
| ![Dark](https://i.imgur.com/YOUR_DARK_SS.png) | ![Light](https://i.imgur.com/YOUR_LIGHT_SS.png) |  

## Project Structure  
```
My_Portfolio/
├── assets/
│   ├── images/       # All project screenshots
│   └── documents/    # CV and PDFs
├── css/
│   └── style.css     # All styling
├── index.html        # No external frameworks
└── README.md
```

## Setup  
1. Clone the repo 
   ```bash
   git clone https://github.com/Martin-Mutugi/My_Portfolio.git
   ```
2. Run locally  
   - Open `index.html` in any browser  

## Key Code Features  
```html
<!-- Pure CSS Theme Toggle -->
<label class="theme-switch">
  <input type="checkbox" id="theme-toggle">
  <span class="slider"></span>
</label>

<!-- CSS Variables for Theming -->
<style>
  :root { --primary: #1a73e8; }
  body.dark-mode { --background: #181a1b; }
</style>


