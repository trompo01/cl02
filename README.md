# 📚 Literary Worlds - Bilingual Book Showcase

A stunning 3D interactive bilingual website showcasing four published books with immersive design and advanced web technologies.

## ✨ Features

- **Bilingual Interface**: Complete Spanish & English support
- **5 Interactive Pages**:
  - Page 1: Welcome/Landing page with language selection
  - Page 2: Español - "Cuando la Familia se Rompe en Silencio"
  - Page 3: Español - "Manual del Inadaptado Lúcido"
  - Page 4: English - "When Families Fracture in Silence"
  - Page 5: English - "The Lucid Misfit's Handbook"

- **Premium Design**:
  - Dark minimalist aesthetic with high contrast
  - 3D perspective effects on all interactive elements
  - Neon glow accents (cyan, gold, purple)
  - Smooth animations and transitions
  - Mouse tilt effects on buttons
  - Sparkling 3D button effects

- **Music Integration**:
  - Background music player (plays kelvin.aac)
  - Auto-play on page load
  - Play/Pause control
  - Loop functionality

- **Responsive Design**:
  - Desktop: Full 3D effects and optimal layout
  - Tablet: Adjusted spacing and touch-friendly
  - Mobile: Stacked layout, readable text, full functionality

- **Book Information**:
  - Detailed book titles and subtitles
  - Author information
  - Multiple purchase links (Amazon, MercadoLibre, Books A Million, Saxo, Bookshop.org)
  - Links to reviews, samples, podcasts
  - Spotify playlists
  - Goodreads links
  - Author profiles

## 📋 Page Structure

### Page 1 - Welcome (Bienvenida)
- Large welcoming title
- Two language buttons with animated flags
- 3D hover effects
- Floating animation

### Pages 2 & 3 - Spanish Books
- Book title and author information
- Comprehensive table with 10 links each:
  - Spotify spoken reviews
  - Communication methods (WhatsApp, Google Meet)
  - Multiple format versions (Kindle, Paperback, Hardcover)
  - Free reading options
  - Review platforms
  - Music and podcast links
  - Goodreads profiles
  - Author information

- Purchase buttons with retailers:
  - Amazon
  - MercadoLibre (Argentina)
  - Books A Million (USA)

- Navigation footer (Next/Previous)

### Pages 4 & 5 - English Books
- Same structure as Spanish pages
- 9 links per book table
- Multiple international retailers:
  - Amazon
  - Books A Million (USA)
  - Books.com.tw (Taiwan)
  - Saxo (Denmark)
  - Bookshop.org (Worldwide)

## 🚀 Getting Started

### Installation

1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/literary-worlds.git
cd literary-worlds
```

2. **Add your audio file**:
   - Place `kelvin.aac` in the root directory
   - Or replace the audio source in index.html with your own file

3. **Deploy to GitHub Pages**:
   - Push to GitHub
   - Enable GitHub Pages in repository settings
   - Select main branch as source
   - Your site will be available at `https://yourusername.github.io/literary-worlds`

### Local Testing

Simply open `index.html` in your web browser. All features work locally including:
- 3D effects
- Animations
- Page navigation
- Music playback (if audio file is present)

## 📱 Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Opera: Full support
- Mobile browsers: Responsive design optimized for iOS and Android

## 🎨 Design Details

### Color Scheme
- **Primary Background**: #0a0e27 (Deep Navy)
- **Secondary Background**: #1a1f3a (Darker Navy)
- **Neon Cyan**: #00d4ff (Glow Effects)
- **Gold**: #d4af37 (Text Accents)
- **Text**: #ffffff (Pure White)

### Effects
- **3D Perspective**: CSS perspective and transform properties
- **Glow Effects**: Box-shadow with neon colors
- **Animations**: 
  - Float (3s ease-in-out)
  - Sparkle (0.6s infinite)
  - Flag scroll (1s ease-in-out)
  - Glow pulse (1.5s ease infinite)

### Typography
- Clean sans-serif fonts
- High contrast white on dark backgrounds
- Clear hierarchy with multiple font sizes
- Readable on all devices

## 🔗 External Links

All links open in new tabs to maintain website navigation:
- Amazon stores (multiple countries)
- MercadoLibre Argentina
- Books A Million USA
- Saxo Denmark
- Bookshop.org
- Spotify playlists
- Goodreads profiles
- Google Calendar (consultation bookings)
- WhatsApp chat

## 📊 Statistics

- **Total Pages**: 5
- **Total Links**: 40+ external connections
- **Supported Languages**: 2 (Spanish & English)
- **Books Featured**: 4
- **Retailers**: 5+ international platforms
- **CSS Classes**: 30+
- **JavaScript Functions**: 10+

## 🎯 Optimization

- **Performance**: Minimal external dependencies
- **SEO-Friendly**: Proper semantic HTML
- **Accessibility**: High contrast ratios (WCAG AA compliant)
- **Speed**: Single HTML file, inline CSS
- **Mobile**: Optimized touch targets and responsive layout

## 📝 Customization

### Change Colors
Edit the CSS variables in the `:root` section:
```css
:root {
    --primary-dark: #0a0e27;
    --accent-neon: #00d4ff;
    --gold: #d4af37;
    /* etc. */
}
```

### Add New Books
1. Duplicate a page section
2. Update book information
3. Add new links in the table
4. Update navigation buttons

### Replace Music
Replace `kelvin.aac` file path with your own audio file (supports: .aac, .mp3, .wav, .ogg)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: 
  - Flexbox and Grid layouts
  - CSS transforms and perspectives
  - CSS animations
  - CSS variables
- **JavaScript (Vanilla)**:
  - DOM manipulation
  - Event listeners
  - Audio controls
  - Page navigation

## 📄 License

This project is open source and available under the MIT License.

## 👤 Authors

- **Books Showcase Design**: Created for Vanina Vergara & Pablo Mera
- **Web Design & Development**: Professional 3D Web Template

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Support

For issues, questions, or suggestions, please open an issue in the GitHub repository.

## 🌟 Credits

Special thanks to:
- Vanina Vergara - Author of "Cuando la Familia se Rompe en Silencio" & "When Families Fracture in Silence"
- Pablo Mera - Author of "Manual del Inadaptado Lúcido" & "The Lucid Misfit's Handbook"

---

**Version**: 1.0.0  
**Last Updated**: May 2024  
**Status**: ✅ Production Ready

## 📦 Files Included

```
literary-worlds/
├── index.html          # Main website (single file)
├── kelvin.aac         # Background music file
├── README.md          # This file
└── .gitignore         # Git ignore file
```

## 🚀 Quick Deploy to GitHub Pages

1. Create a new GitHub repository named `literary-worlds`
2. Clone it locally
3. Add these files:
   - index.html
   - kelvin.aac
   - README.md
4. Push to GitHub:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```
5. Go to repository Settings → Pages
6. Select "main" branch as source
7. Your site is live! 🎉

Enjoy your beautiful book showcase! 📚✨
