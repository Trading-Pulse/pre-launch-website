# Trading Pulse - Pre-Launch Website

A responsive pre-launch landing page for Trading Pulse, a trading alerts platform that delivers real-time buy and sell signals through custom technical analysis indicators.

## 🌐 Live Site
[tradingpulse.io](https://tradingpulse.io)

## 📋 Overview

This is the official pre-launch website for Trading Pulse, designed to capture early user interest and build a waitlist before the platform launches. The site showcases the core value proposition of never missing trading opportunities through intelligent, customizable alerts.

## ✨ Features

### 🎯 Core Functionality
- **Waitlist Registration**: HubSpot-integrated form for capturing early signups
- **Responsive Design**: Mobile-first approach ensuring optimal experience across all devices
- **SEO Optimized**: Proper meta tags, semantic HTML, and Google Tag Manager integration
- **Performance Focused**: Tailwind CSS for optimized styling and fast loading times

### 🎨 Design Elements
- **Hero Section**: Eye-catching gradient background with trading imagery
- **Step-by-step Process**: Clear explanation of how Trading Pulse works
- **Benefits Showcase**: Highlights of exclusive launch benefits
- **Sticky Header**: Easy navigation with prominent CTA button
- **Custom Styling**: Branded color scheme and typography

### 📊 Analytics & Tracking
- Google Tag Manager implementation (`GTM-PVSFMX5R`)
- Conversion tracking for waitlist signups
- User engagement monitoring

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Tailwind CSS v3.3.0
- **Build Tools**: Tailwind CLI
- **Forms**: HubSpot Forms API
- **Analytics**: Google Tag Manager
- **Hosting**: GitHub Pages (custom domain: tradingpulse.io)

## 🚀 Getting Started

### Prerequisites
- Node.js (for Tailwind CSS compilation)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Pre_Launch
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Build CSS for development** (with watch mode)
   ```bash
   npm run build-css
   ```

4. **Build CSS for production** (minified)
   ```bash
   npm run build
   ```

5. **Open in browser**
   ```bash
   open index.html
   ```

## 📁 Project Structure

```
Pre_Launch/
├── index.html              # Main landing page
├── package.json            # Dependencies and scripts
├── tailwind.config.js      # Tailwind CSS configuration
├── CNAME                   # Custom domain configuration
├── src/
│   └── input.css          # Source CSS with Tailwind directives
├── dist/
│   └── output.css         # Compiled CSS (generated)
└── images/
    ├── logo.svg           # Trading Pulse logo
    └── buy_sell.jpg       # Hero background image
```

## 🎨 Customization

### Brand Colors
The project uses a custom color palette defined in `tailwind.config.js`:
- **Pulse Blue**: `#1e40af` - Primary brand color
- **Pulse Dark**: `#1e293b` - Dark backgrounds and text
- **Pulse Green**: `#059669` - Call-to-action buttons

### Custom Components
Pre-defined CSS classes for consistent styling:
- `.btn-primary` - Main call-to-action buttons
- `.btn-secondary` - Secondary action buttons
- `.gradient-hero` - Hero section background
- `.step-circle` - Process step indicators
- `.benefit-card` - Feature highlight cards

## 📝 Content Sections

1. **Hero Section**: Main value proposition and primary CTA
2. **How It Works**: 3-step process explanation
3. **Why Join Now**: Benefits of early signup with waitlist form
4. **Closing CTA**: Final conversion opportunity

## 🔧 Development

### Building CSS
The project uses Tailwind CSS for styling. Two build commands are available:

- **Development**: `npm run build-css` - Watches for changes and rebuilds
- **Production**: `npm run build` - Creates minified output for deployment

### Form Integration
The waitlist form uses HubSpot's embedded forms:
- **Portal ID**: 442240047
- **Form ID**: 6c4083be-aeef-45a8-928b-b86308627ea0
- **Region**: ap1 (Asia Pacific)

## 🚀 Deployment

The site is automatically deployed to GitHub Pages and served at `tradingpulse.io`. Any changes pushed to the main branch will be reflected on the live site.

### Deployment Checklist
- [ ] Run `npm run build` to generate minified CSS
- [ ] Commit and push changes to main branch
- [ ] Verify live site reflects updates
- [ ] Test form functionality and analytics tracking

## 📈 Performance & Analytics

- **Google Tag Manager**: Tracks user interactions and conversions
- **Optimized Assets**: Compressed images and minified CSS
- **Responsive Images**: Proper sizing for different screen resolutions
- **Smooth Scrolling**: Enhanced user experience with CSS scroll behavior

## 🤝 Contributing

1. Make changes to source files (`index.html`, `src/input.css`)
2. Build CSS with `npm run build-css` during development
3. Test across different browsers and devices
4. Build production CSS with `npm run build` before deployment
5. Commit and push changes

## 📞 Contact

For questions about the pre-launch website or Trading Pulse platform, visit [tradingpulse.io](https://tradingpulse.io) and join our waitlist.
