# Money On Da Flo ENT - Music Studio Landing Page

A cutting-edge landing page for Money On Da Flo ENT music studio with integrated Cal.com booking functionality.

## Features

- Modern, responsive design with black, red, and green color scheme
- Smooth animations and transitions
- Mobile-friendly navigation
- Cal.com booking integration for easy session scheduling
- Services showcase
- Studio features highlight
- Contact form
- Optimized for Netlify deployment

## Cal.com Integration Setup

To complete the Cal.com integration:

1. Create a Cal.com account at [cal.com](https://cal.com)
2. Set up your booking calendar and availability
3. Get your Cal.com username or team name
4. Update the Cal.com embed code in `index.html`:
   - Find `data-cal-link="team/moneyondafloor-ent"`
   - Replace `"team/moneyondafloor-ent"` with your actual Cal.com username/team
   - Example: `data-cal-link="yourusername"` or `data-cal-link="team/yourteam"`

## Deployment to Netlify

### Option 1: Drag and Drop
1. Create a Netlify account at [netlify.com](https://netlify.com)
2. Drag and drop the entire project folder to Netlify's deployment page
3. Your site will be live!

### Option 2: Git Integration
1. Push this code to a GitHub repository
2. Connect your Netlify account to GitHub
3. Select the repository
4. Netlify will automatically detect the `netlify.toml` configuration
5. Deploy!

## Local Development

To run locally:

```bash
python3 -m http.server 5000
```

Then open `http://localhost:5000` in your browser.

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --red: #ff0000;
    --green: #00ff00;
    --black: #0a0a0a;
}
```

### Content
- Update contact information in the Contact section of `index.html`
- Add your studio address, phone number, and email
- Update social media links
- Customize service descriptions and studio features

### Images
- Replace `generated-icon.png` with your studio logo
- Add studio photos to enhance the visual appeal

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables, Animations)
- Vanilla JavaScript
- Cal.com Embed
- Google Fonts (Orbitron, Inter)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

© 2024 Money On Da Flo ENT. All rights reserved.
