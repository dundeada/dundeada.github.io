# 🚗 Els Auto Rentals

Premium car rental service in St Vincent. Book Economy, Premium, and Luxury vehicles online with competitive rates, 24/7 support, and full insurance coverage.

**Website**: [elsautorentals.com](https://dundeada.github.io)

## ✨ Features

### Stunning Design & Performance
- **Cinematic glassmorphism** with dynamic lighting effects
- **Smooth scroll animations** with parallax storytelling
- **Magnetic cursor system** with context-aware interactions
- **Web Audio API** synthesized sound effects
- **60fps hardware-accelerated** animations
- **Fully responsive** across all devices
- **Zero dependencies** - Pure vanilla HTML5, CSS3, JavaScript

### User Experience
- **Fast online booking** system
- **Transparent pricing** with no hidden fees
- **24/7 customer support** contact
- **Fleet showcase** (Economy, Premium, SUV, Luxury)
- **Pricing comparison** for all vehicle classes
- **Customer testimonials** and social proof
- **Google Analytics 4** event tracking

## 🚗 Vehicle Classes

| Class | Starting Price | Features |
|-------|-----------------|----------|
| **Economy** | $35/day | Fuel-efficient, affordable |
| **Premium Sedan** | $65/day | Comfort, style, business-ready |
| **SUV** | $85/day | Spacious, adventure-ready |
| **Luxury** | $150/day | Premium features, concierge |

*All rates include: unlimited mileage, full insurance, roadside assistance, and 24/7 support*

## 📍 Service Area

**St Vincent & The Grenadines**
- Airport pick-up available
- Downtown locations
- Resort area delivery options

## 🚀 Getting Started

### Local Development
```bash
# Clone the repository
git clone https://github.com/dundeada/dundeada.github.io.git
cd dundeada.github.io

# Serve locally (Python 3)
python3 -m http.server 8000

# Or with Node.js
npx http-server

# Visit http://localhost:8000
```

### Customization

#### 1. **Update Tracking ID**
Replace Google Analytics placeholder in `index.html` (line ~24):
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
```

#### 2. **Update Contact Information**
- Email: Update in footer and form handler
- Phone: Update in footer social links
- Locations: Update in Services section

#### 3. **Change Pricing**
Edit Pricing Section (~line 620):
```html
<h3 class="portfolio-title">Economy</h3>
<p class="portfolio-description">From $35/day. Fuel-efficient and perfect for exploring the island</p>
```

#### 4. **Customize Vehicle Classes**
Edit Fleet Section (~line 550) with your specific offerings

#### 5. **Update Brand Colors**
Edit CSS variables in `index.html` (~lines 50-70):
```css
:root {
    --color-dark-0: #0a0e1a;              /* Background */
    --color-accent-cyan: #00d9ff;         /* Primary accent */
    --color-accent-violet: #0066ff;       /* Secondary accent */
}
```

## 📋 File Structure

```
/dundeada.github.io/
├── index.html (2000+ lines - complete site)
├── netlify.toml (Deployment config)
├── .gitignore (Git ignore rules)
├── README.md (This file)
├── LICENSE
└── .git/ (Version control)
```

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free) ✅
```bash
# Already deployed!
git push origin main
# Live at: https://dundeada.github.io
```

### Option 2: Netlify (Recommended for Forms)
```bash
1. Connect GitHub repository to netlify.com
2. Deploy automatically
3. Enable form notifications in dashboard
4. Forms submitted via booking form will be emailed to you
```

**Features**: 
- Form handling with email notifications
- 24/7 uptime monitoring
- Automatic HTTPS
- CDN edge caching

### Option 3: Custom Domain
1. Purchase domain (e.g., elsautorentals.com)
2. Point DNS to GitHub Pages or Netlify
3. Configure in repository settings

### Option 4: Traditional Hosting
Upload all files via FTP/SFTP to your web server

## 📊 Analytics & Tracking

Google Analytics 4 events tracked:
- **Booking requests** - Track form submissions
- **Fleet exploration** - Track which vehicles users explore
- **Scroll depth** - Monitor engagement (25%, 50%, 75%)
- **Social clicks** - Track social media link clicks
- **Call button** - Track phone inquiries

View data in Google Analytics dashboard

## 🎨 Design System

### Colors
- **Primary Background**: `--color-dark-0` (#0a0e1a)
- **Primary Accent**: `--color-accent-cyan` (#00d9ff)
- **Secondary Accent**: `--color-accent-violet` (#0066ff)
- **Text Primary**: `--color-text-primary` (#ffffff)
- **Text Secondary**: `--color-text-secondary` (#a8b5c7)

### Typography
- **Headers**: Cinzel (serif)
- **Display**: Syne (sans-serif)
- **Body**: Plus Jakarta Sans (sans-serif)

### Spacing & Motion
- Fast transitions: 0.2s
- Standard animations: 0.4s
- Dramatic reveals: 0.8s

## 📱 Browser Support

| Browser | Status | Notes |
|---------|--------|-------|
| Chrome/Edge | ✅ Full | Best performance |
| Firefox | ✅ Full | Excellent support |
| Safari | ✅ Full | iOS & macOS optimized |
| Mobile | ✅ Full | Touch-optimized |
| IE 11 | ❌ No | Not supported |

## 🛠️ Troubleshooting

### Audio Not Playing
- Audio requires user interaction (click/scroll first)
- Check browser console for errors
- Ensure system audio is not muted

### Forms Not Submitting
- For GitHub Pages: Use Netlify instead
- For Netlify: Ensure `netlify` attribute on form
- Check Netlify dashboard > Forms tab

### Performance Issues
- Reduce particle count in JavaScript (~line 380)
- Disable animations on mobile
- Test with DevTools Performance profiler

## 📧 Support

**Contact**: bookings@elsautorentals.com  
**Phone**: +1 (784) 000-0000  
**Hours**: 24/7

## 📜 License

© 2026 Els Auto Rentals. All rights reserved.

---

**Built with ❤️ for premium car rental experiences.**
first git hub site 
