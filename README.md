# 🚀 Nguyễn Gia Bảo — Portfolio

Personal portfolio website built with HTML, CSS, and Vanilla JavaScript.

## 🗂 Project Structure

```
portfolio/
├── index.html      # Main HTML file
├── style.css       # Styles (dark cyberpunk theme)
├── script.js       # Interactions & animations
└── README.md       # This file
```

## ⚡ Setup & Run

### Option 1: Open directly (simplest)
Just double-click `index.html` — it works offline, no build step needed!

### Option 2: Local development server (recommended for live-reload)

**Using VS Code + Live Server (recommended):**
1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Install the **Live Server** extension (Ritwick Dey)
3. Open the `portfolio/` folder in VS Code
4. Right-click `index.html` → **"Open with Live Server"**
5. Browser opens at `http://127.0.0.1:5500`

**Using Node.js (npx serve):**
```bash
npx serve .
# Opens at http://localhost:3000
```

**Using Python:**
```bash
# Python 3
python -m http.server 8080
# Opens at http://localhost:8080
```

## 🌐 Deploy to GitHub Pages (Free Hosting)

1. Create a new GitHub repo named `portfolio` (or `<your-username>.github.io`)
2. Push all files:
```bash
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/nguyengiabao91753/portfolio.git
git push -u origin main
```
3. Go to repo **Settings → Pages**
4. Source: **Deploy from branch → main → / (root)**
5. Your site will be live at: `https://nguyengiabao91753.github.io/portfolio/`

## ✏️ Customization

- **Add your photo**: Replace the `avatar-initials` div in `index.html` with an `<img>` tag
- **Add LinkedIn**: Add your LinkedIn URL in the hero-socials section
- **CV download**: Add a resume PDF to the folder and link it in the About section
- **Update info**: Edit `index.html` directly — all content is clearly labeled

## 🎨 Tech Used

- Fonts: [Syne](https://fonts.google.com/specimen/Syne) + [Space Mono](https://fonts.google.com/specimen/Space+Mono)
- Icons: [Font Awesome 6](https://fontawesome.com/)
- Pure CSS animations (no framework)
- Vanilla JavaScript (no dependencies)
