# 🍛 Hotel Rajeshwari - Website

**Live Site:** https://YOUR_USERNAME.github.io

## How to Deploy (Git Bash Steps)

```bash
# 1. Go to your project folder
cd rajeshwari

# 2. Initialize git
git init

# 3. Add all files
git add .

# 4. Commit
git commit -m "Initial website launch 🚀"

# 5. Add your GitHub repo as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git

# 6. Push to GitHub
git push -u origin main
```

## How to Update Menu / Timing
- Open `index.html` in any text editor (Notepad++, VS Code)
- Find `const menuData = {` to edit menu items & prices
- Find `const schedule = {` to edit opening hours
- Save file, then run:
```bash
git add .
git commit -m "Updated menu"
git push
```
Site updates in ~2 minutes!

## Features
- Live clock & open/closed status
- Full menu with 5 categories (30+ items)
- WhatsApp ordering (direct to your number)
- Contact form → sends to WhatsApp
- Mobile responsive
- Floating WhatsApp button
- Auto-updates open/closed based on real time

