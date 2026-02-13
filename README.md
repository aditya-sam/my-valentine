# 💝 Be My Valentine? - Web App

A cute, playful single-page React app to ask your girlfriend to be your Valentine!

## 🚀 Quick Start

1. Open `index.html` in any web browser
2. That's it! No build process or installation needed.

## ✨ Features

- ✅ Playful "Yes" and "No" buttons
- ✅ Yes button grows bigger each time No is clicked (up to 3x size)
- ✅ Randomized playful messages when No is clicked (no repeats until all 7 are exhausted)
- ✅ Celebration with heart confetti animation when Yes is clicked
- ✅ Success screen with GIF and Swiggy Dineout link
- ✅ Fully responsive and mobile-friendly
- ✅ Beautiful pink-red Valentine gradient theme
- ✅ Accessible (ARIA labels and semantic HTML)

## 🎨 Customization Guide

### 1. **Add Your Celebration GIF**
Find line with `YOUR_FUNNY_GIF_URL_HERE` and replace it with your GIF URL.

Example sources:
- Giphy: https://giphy.com/
- Tenor: https://tenor.com/

```html
<!-- Before -->
<img src="YOUR_FUNNY_GIF_URL_HERE" ...>

<!-- After -->
<img src="https://media.giphy.com/media/3oz8xAFtqoOUUrsh7W/giphy.gif" ...>
```

### 2. **Add Your Swiggy Dineout Link**
Find line with `YOUR_SWIGGY_DINEOUT_LINK_HERE` and replace with your reservation link.

```html
<!-- Before -->
<a href="YOUR_SWIGGY_DINEOUT_LINK_HERE" ...>

<!-- After -->
<a href="https://www.dineout.co.in/booking/your-restaurant" ...>
```

### 3. **Customize Playful Messages**
Edit the `playfulMessages` array in the JavaScript section:

```javascript
const playfulMessages = [
    "Oops! Everyone is allowed one mistake — try again 😉",
    "Wrong answer! Try again…",
    // Add or modify messages here!
];
```

### 4. **Change Colors**
Look for color comments in the CSS section:
- Main Valentine color: `#ff4d6d` (search for this in CSS)
- Background gradient: Lines with `background: linear-gradient(...)`
- Button colors: `.yes-button` and `.no-button` classes

### 5. **Update Footer**
Find the footer div:
```html
<div class="footer">
    Made with ❤️ by Aditya
</div>
```

## 📱 Mobile Friendly

The app automatically adapts to phone screens with responsive breakpoints at:
- 600px and below
- 400px and below (small phones)

## 🎭 How It Works

1. **Initial State**: Shows question with Yes and No buttons
2. **No Button**: Each click makes Yes button grow + shows random playful message
3. **Yes Button**: Triggers celebration animation + shows success screen with GIF and booking link

## 🛠️ Technical Details

- **React 18** via CDN (no build tools needed)
- **Babel Standalone** for JSX transformation
- **Pure CSS** animations and styling
- **No external dependencies** required
- **Single file** - easy to share and deploy

## 🌐 Deployment Options

### Option 1: Open Locally
Just double-click `index.html`

### Option 2: Host Online (Free)
- **Netlify Drop**: Drag and drop index.html to https://app.netlify.com/drop
- **GitHub Pages**: Push to a repo and enable GitHub Pages
- **Vercel**: Import folder and deploy

## 💡 Tips

- Test on mobile before sharing!
- The Yes button grows up to 3× its original size
- Messages rotate without repeats until all 7 are used, then reshuffle
- The confetti animation lasts 5 seconds
- Use a high-quality GIF (under 5MB recommended for fast loading)

## ❤️ Perfect for

- Valentine's Day proposals
- Anniversary surprises
- Cute date requests
- Making your girlfriend smile 😊

---

**Made with ❤️ by Aditya**
