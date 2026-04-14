# Radha Sakthi - IT Consulting & Software Development

A professional website for Radha Sakthi, an IT consulting and software development company based in Austin, TX.

## Design Philosophy

The design blends modern IT professionalism with traditional Indian aesthetics, featuring:
- Peacock feather-inspired color palette (deep blue, teal, gold, emerald)
- Peacock eye motif in the logo and decorative elements
- Clean, modern typography with Playfair Display and Inter fonts

## Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Deep Blue | #1a237e | Primary dark accent |
| Royal Blue | #1a73e8 | Primary actions |
| Teal | #00897b | Secondary accent |
| Gold | #ffc107 | Highlight accent |
| Emerald | #2e7d32 | Success states |

## Project Structure

```
radhasakthi/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # Interactive features
├── images/
│   └── favicon.svg     # Peacock feather favicon
└── README.md
```

## Features

- Fully responsive design
- Smooth scroll navigation
- Mobile-friendly hamburger menu
- Contact form with validation
- Scroll-triggered animations
- Counter animations for statistics

## Deployment to AWS

### Option 1: S3 Static Website Hosting

1. Create an S3 bucket named `radhasakthi.com`
2. Enable static website hosting
3. Upload all files
4. Configure bucket policy for public access
5. Point your domain to the S3 website endpoint

### Option 2: CloudFront + S3 (Recommended)

1. Create an S3 bucket (doesn't need to be public)
2. Create a CloudFront distribution
3. Set S3 as the origin with OAI
4. Configure custom domain and SSL certificate
5. Update Route 53 to point to CloudFront

## Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Copyright 2024 Radha Sakthi. All rights reserved.
