# 💻 Martin Mutugi - Portfolio  
[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR_BADGE_ID/deploy-status)](https://martinmutugiportfolio.netlify.app/)  

## 🎯 Features  
- **Dark/Light Mode**: CSS variable-powered theme switching  
- **Interactive Projects**: Real-time chat app with 10k+ user capacity  
- **Performance**: 95+ Lighthouse score (verified)  

## 🚀 Tech Stack  
| Area       | Technologies Used |  
|------------|-------------------|  
| Frontend   | HTML5, CSS3, JavaScript |  
| Backend    | FormSubmit (Contact Form) |  
| Hosting    | Netlify |  

## 📸 Preview  
| Dark Mode | Light Mode |  
|-----------|------------|  
| ![Dark](https://i.imgur.com/YOUR_DARK_SS.png) | ![Light](https://i.imgur.com/YOUR_LIGHT_SS.png) |  

## 🔧 How to Run Locally  
```bash
git clone https://github.com/Martin-Mutugi/My_Portfolio.git  
cd My_Portfolio  
open index.html  # Runs in default browser


**Action Items:**  
- [ ] Add real screenshots (use [LightShot](https://app.prntscr.com/) for quick captures)  
- [ ] Get your Netlify badge ID from [Netlify Badges](https://docs.netlify.com/monitor-sites/notifications/#badges)  

---

### 🔍 **Codebase Improvements**  
**1. Comment Key Sections** *(Add to `index.html`)*:  
```html
<!-- THEME TOGGLE: Uses CSS variables for dynamic switching -->  
<button id="theme-toggle">🌙</button>  

<!-- PROJECTS: Dynamically loaded from projects[] array -->  
<section id="projects"></section>

My_Portfolio/  
├── assets/  
│   ├── images/       # Move profile pics here  
│   └── docs/         # PDFs like CV  
├── css/              # Create this  
│   └── style.css     # Move CSS here  
├── js/               # Create this  
│   └── main.js       # Move scripts here  
├── index.html  
└── README.md    
