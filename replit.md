# Money On Da Flo ENT - Music Studio Landing Page

## Project Overview
A cutting-edge static landing page for Money On Da Flo ENT music studio featuring a modern design with black, red, and green color scheme. The site includes Cal.com booking integration for seamless studio session scheduling and is optimized for deployment on Netlify.

## Current State
- Static HTML/CSS/JavaScript website
- Fully responsive design
- Cal.com booking widget embedded and configured (https://cal.com/moneyondafloent/30min)
- Contact information centered and updated
- Ready for Netlify deployment
- Local development server running on port 5000

## Recent Changes (November 12, 2025)
- Updated hero title from "Floor" to "FLO" with gradient effect
- Updated all branding references to "Money On Da Flo ENT"
- Removed Mixing service card (now showing 3 services: Recording, Mastering, Production)
- Added animated falling dollar bills (💵) background effect with rotation and fade
- Removed contact form completely
- Centered contact section content
- Updated contact information:
  - Email: moneyondafloent@gmail.com
  - Location: East Nashville
  - Removed phone number
- Updated Cal.com booking link to moneyondafloent/30min
- Fixed Cal.com deprecation warning (replaced styles with cssVarsPerTheme)
- Replaced generated-icon.png with custom logo.jpg
- Updated Netlify caching configuration
- Fixed JavaScript errors by removing contactForm references from script.js
- Added cache-busting: script.js?v=2 to force fresh JavaScript loading
- Added cache-control meta tags to prevent HTML caching issues

## Project Architecture

### File Structure
```
/
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete styling with animations
├── script.js           # Interactive functionality
├── logo.jpg            # Custom studio logo with money stacks
├── netlify.toml        # Netlify deployment configuration
├── README.md           # Setup and deployment instructions
├── .gitignore          # Git ignore rules
└── replit.md           # This file
```

### Key Features
1. **Hero Section**: Full-screen hero with animated "Money on da FLO" title and falling money animation
2. **Services**: Grid layout showcasing 3 services (Recording, Mastering, Production)
3. **Studio Features**: Highlights of equipment and amenities
4. **Booking Section**: Cal.com embed for session scheduling (moneyondafloent/30min)
5. **Contact Section**: Centered contact information (location, email, social links)
6. **Responsive Design**: Mobile-first approach with breakpoints

### Technology Stack
- Pure HTML5, CSS3, Vanilla JavaScript
- No build process required
- Cal.com embed script (with updated cssVarsPerTheme API)
- Google Fonts (Orbitron, Inter)
- Animated background effects

### Color Scheme
- Primary: Black (#0a0a0a)
- Accent 1: Red (#ff0000)
- Accent 2: Green (#00ff00)
- Text: White (#ffffff) and Gray (#b0b0b0)
- Gradient on "FLO": Orange to green

### Contact Information
- Location: East Nashville
- Email: moneyondafloent@gmail.com
- Cal.com: https://cal.com/moneyondafloent/30min
- Social media: Instagram, Twitter, YouTube (placeholder links)

## User Preferences
- Cutting-edge, modern design aesthetic
- Black, red, and green color palette
- "Money On Da Flo ENT" branding (not "Floor")
- Cal.com integration for bookings
- Static site for Netlify deployment
- Centered contact information
- No contact form

## Next Steps for User
1. Update social media links with actual URLs
2. Consider adding custom studio photos/images
3. Deploy to Netlify (all files ready)
4. Test Cal.com booking integration

## Deployment Notes
- Configured for Netlify with netlify.toml
- No build process required (pure static files)
- All files should be deployed as-is
- Caching headers optimized for performance
- Cal.com embed uses latest API (cssVarsPerTheme)
