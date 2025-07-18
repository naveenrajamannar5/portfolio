# My Portfolio Website

A modern, responsive portfolio website built with HTML and CSS.

## Structure
- `index.html` - Main webpage
- `styles.css` - Styling
- `assets/` - Images and other media files
- `Brown and Cream Modern Portfolio Presentation.pdf` - Portfolio presentation

## Deployment Instructions

### Option 1: GitHub Pages (Recommended)
1. Create a new repository on GitHub
2. Push these files to your repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```
3. Go to repository Settings > Pages
4. Under "Source", select "main" branch
5. Click Save - your site will be live at `https://yourusername.github.io/portfolio`

### Option 2: AWS S3 + CloudFront (Free Tier)
1. Create an S3 bucket
2. Enable static website hosting
3. Upload these files to your bucket
4. Create a CloudFront distribution
5. Point your domain to CloudFront (optional)

Detailed AWS setup guide: [AWS Static Website Hosting](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html)

## Customization
1. Replace placeholder text in `index.html`
2. Update contact links (email, LinkedIn, GitHub)
3. Add your own images to `assets/`
4. Modify colors in `styles.css` (look for `:root` variables)

## Local Development
Just open `index.html` in your browser to preview changes.

## Credits
- Icons: Font Awesome
- Fonts: Inter, System fonts 