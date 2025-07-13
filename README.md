# Deathtrip 🚗💀

A powerful traffic safety awareness campaign website focused on preventing impaired driving. This project delivers a stark message about the dangers of driving under the influence through impactful visual design and typography.

## 🎯 Project Overview

**Deathtrip** is a single-page awareness website created in partnership with "Ung i Trafikken" (Youth in Traffic) to educate about the deadly consequences of impaired driving. The site uses dark themes and striking visuals to create a memorable impact on visitors.

## ✨ Features

- **🎨 Dark Theme Design**: Professional dark blue color scheme (#214E5F) with cyan accents
- **⚠️ Warning Imagery**: Prominent triangle warning sign to grab attention  
- **📱 Responsive Layout**: Adapts to different screen sizes with proper viewport settings
- **🎭 Typography Focus**: Custom typewriter-style fonts for serious messaging
- **🎪 Visual Hierarchy**: Bordered boxes and sections to guide user attention
- **💫 Smooth Animations**: Bouncing arrow animation for engagement

## 🗂️ Project Structure

```
deathtrip/
├── index.html              # Main HTML file
├── assets/
│   └── 3bc22557f744fa09... # Ung i Trafikken logo
├── LICENSE                 # MIT License
└── README.md              # This documentation
```

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone [repository-url]
cd deathtrip
```

2. **Open in browser**
```bash
# Simply open the HTML file
open index.html
# or
firefox index.html
```

3. **No build process required!** ✅ Pure HTML/CSS implementation

## 💻 Technical Implementation

### 🎨 CSS Architecture

The styling uses a cohesive color palette and custom typography:

```css
/* Main theme colors */
html {
    background-color: #214E5F;  /* Deep blue-gray */
}

main {
    background-color: #214E5F;
    color: #C9F2F7;             /* Light cyan text */
    font-family: 'Bulletin Typewriter MN', 'Courier New', Courier, monospace;
}

/* Attention-grabbing red accent */
#vissteduat {
    color: #FF0000;             /* Bright red for emphasis */
}
```

### 📦 Component Structure

**Message Box Component:**
```html
<div class="box">
    <div class="inner-box">
        <p>Visste du at all <br> rus kan beruse deg?<br> Kjør edru!</p>
    </div>
</div>
```

**Animated Arrow:**
```css
@keyframes bounce {
    0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
    }
    40% {
        transform: translateY(-30px);
    }
    60% {
        transform: translateY(-15px);
    }
}
```

### 🖼️ Image Integration

The project uses both local assets and external images:

```html
<!-- Local logo -->
<img id="ungitrafikken" src="assets/3bc22557f744fa09e19a58f2856b759594ec397e-3600x847.png">

<!-- External warning sign via Wikimedia Commons -->
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/59/Triangle_warning_sign_%28red_and_white%29.svg/256px-Triangle_warning_sign_%28red_and_white%29.svg.png">
```

## 🎭 Design Philosophy

### Visual Impact Elements
- **🔷 Bordered boxes** for message containment
- **⚠️ Warning triangles** for immediate attention
- **💀 Dark themes** to convey seriousness
- **🔴 Red accents** for critical information
- **📖 Typewriter fonts** for authoritative messaging

### Message Hierarchy
1. **Primary Message**: "Visste du at all rus kan beruse deg? Kjør edru!"
2. **Secondary Shock**: "visste du at alle dør en gang?"
3. **Visual Support**: Warning signs and imagery

## 🌐 Browser Compatibility

✅ **Supported Browsers:**
- Chrome/Chromium 60+
- Firefox 55+
- Safari 12+
- Edge 79+

✅ **Mobile Responsive:**
- iPhone/iPad Safari
- Android Chrome
- Mobile Firefox

## 🎨 Customization Guide

### 🎯 Changing Colors

```css
/* Update main theme */
html, main {
    background-color: #YOUR_COLOR;
}

/* Update text color */
main {
    color: #YOUR_TEXT_COLOR;
}

/* Update accent color */
#vissteduat {
    color: #YOUR_ACCENT_COLOR;
}
```

### 📝 Updating Messages

```html
<!-- Edit the main message -->
<div class="inner-box">
    <p>Your custom message here</p>
</div>

<!-- Edit the secondary message -->
<h2><span id="vissteduat">custom accent</span> your message here</h2>
```

### 🖼️ Adding New Images

```html
<!-- Add to assets folder and reference -->
<img src="assets/your-image.png" alt="Description">
```

## 📱 Responsive Features

The design adapts to different screen sizes:

```css
/* Mobile-first approach */
main {
    padding-left: 80px;
    padding-right: 80px;
}

/* Flexible image sizing */
section img {
    width: 400px;
    max-width: 100%;
}
```

## 🚨 Important Notes

- **🎯 Target Audience**: Young drivers and traffic safety advocates
- **📢 Message**: Anti-impaired driving awareness
- **🎨 Tone**: Serious, impactful, memorable
- **⚖️ Ethics**: Responsible messaging about life-and-death consequences

## 🤝 Contributing

1. Fork the repository 🍴
2. Create a feature branch 🌿
3. Make your changes ✏️
4. Test across browsers 🧪
5. Submit a pull request 📤

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License
Copyright (c) 2025 William Berge Grønsberg
```

## 👥 Credits

- **🏢 Organization**: Ung i Trafikken (Youth in Traffic)
- **👨‍💻 Developer**: William Berge Grønsberg
- **🎨 Design**: Custom dark theme implementation
- **📸 Assets**: Wikimedia Commons warning signs

## 🔗 External Resources

- [Ung i Trafikken](https://www.ungitrafikken.no/) - Official organization website
- [Wikimedia Commons](https://commons.wikimedia.org/) - Warning sign imagery
- [Web Fonts](https://fonts.google.com/) - Typography resources

## 🎯 Future Enhancements

- [ ] 📊 Add statistics about impaired driving
- [ ] 🎮 Interactive quiz about traffic safety
- [ ] 📱 Progressive Web App features
- [ ] 🌍 Multi-language support
- [ ] 📈 Analytics integration
- [ ] 🔊 Audio warnings/messages
- [ ] 📝 Testimonials section
- [ ] 🎥 Video content integration

---

**⚠️ Remember: Drive sober, arrive alive! 🚗💚**
