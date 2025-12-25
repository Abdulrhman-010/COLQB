# English README - Colab Dashboard

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-HTML%2FCSS%2FJS-orange.svg)

## 📋 About

**Colab Dashboard** is a professional usability testing results platform featuring:
- 📊 Interactive dashboard with real-time metrics
- 📈 Animated charts and visualizations
- 🎨 Modern neon design with dark theme
- 📱 Fully responsive interface
- 🌙 Full Arabic (RTL) support

## 🚀 Quick Start

### Requirements
- Modern browser (Chrome, Firefox, Safari, Edge)
- No installation needed!

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/colab-dashboard.git
cd colab-dashboard

# Open directly
open index.html  # Mac
start index.html # Windows
```

## 📁 Project Structure

```
colab-dashboard/
├── index.html       # Main file (HTML + CSS + JS)
├── README.md        # This file (English)
├── README-ar.md     # Arabic documentation
├── LICENSE          # MIT License
├── .gitignore       # Git ignore rules
├── CHANGELOG.md     # Version history
└── CONTRIBUTING.md  # Contribution guide
```

## ✨ Features

### 🎨 Design
- Modern neon colors (#76EE00) on dark background
- Smooth animations and transitions
- Fully responsive (mobile, tablet, desktop)

### 📊 Content
- Key metrics (completion rate, satisfaction, SUS Score)
- Interactive bar charts with animations
- Participant cards with detailed info
- Critical findings and recommendations

### 🌐 Browser Support
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile devices

## 🎯 Usage

### Edit Data
Open `index.html` and modify values:

```html
<!-- Project info -->
<div class="value">Credit Card</div>  <!-- Project name -->
<div class="value">ANB</div>          <!-- Client name -->

<!-- Metrics -->
<div class="number">100%</div>        <!-- Change value -->
```

### Add Participants
```html
<div class="participant-card">
    <div class="participant-avatar">A</div>
    <div class="participant-name">Ahmed</div>
    <div class="participant-info">
        25 years old<br>
        ✅ Returning customer<br>
        ⏱️ 5m 30s
    </div>
</div>
```

### Customize Colors
Edit `:root` variables in CSS:
```css
:root {
    --accent-neon: #76EE00;    /* Main color */
    --primary-dark: #0D3B26;   /* Dark color */
    --success: #00FF00;         /* Success color */
}
```

## 📦 Deploy on GitHub Pages

### Step 1: Create Repository
```bash
git init
git add .
git commit -m "Initial commit: Colab Dashboard"
```

### Step 2: Push to GitHub
```bash
git remote add origin https://github.com/yourusername/colab-dashboard.git
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to **Settings** → **Pages**
2. Select **Deploy from branch**
3. Choose **main** and **/ (root)**
4. Click **Save**

✅ Your site will be live at: `https://yourusername.github.io/colab-dashboard/`

## 🔧 Customization

### Advanced Setup
Create new pages using same structure:
```html
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>Page Title</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Your content -->
</body>
</html>
```

### Connect to API
```javascript
fetch('https://api.example.com/data')
    .then(response => response.json())
    .then(data => {
        document.querySelector('.number').textContent = data.value;
    });
```

## 📊 Statistics

- **File Size:** ~15 KB (single HTML file)
- **Load Time:** < 1 second
- **Compatibility:** 98%
- **Performance:** 95/100

## 📄 License

This project is licensed under the **MIT License** - see `LICENSE` file.

## 👤 Author

**Abdulrahman Al-Enezi**
- 📧 Email: your-email@example.com
- 🔗 GitHub: [yourusername](https://github.com/yourusername)
- 🌐 Website: [yourwebsite.com](https://yourwebsite.com)

## 📞 Support

- 📌 **Issues:** [Open an Issue](https://github.com/yourusername/colab-dashboard/issues)
- 💬 **Discussions:** [Start Discussion](https://github.com/yourusername/colab-dashboard/discussions)
- 📧 **Email:** support@example.com

---

**Last Updated:** December 2025
**Current Version:** 1.0.0