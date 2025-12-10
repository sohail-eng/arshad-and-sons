# ARSHED & SONS ENTERPRISES - Business Website

A modern, professional, and mobile-responsive website for ARSHED & SONS ENTERPRISES - a chemical suppliers business based in Faisalabad, Pakistan.

## Features

- 🎨 Modern and eye-catching design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading and optimized performance
- 🎯 SEO-friendly structure
- 🔄 Smooth animations and transitions
- 📋 Company information display
- 💼 Banking details with copy-to-clipboard functionality
- 📞 Contact information with clickable links

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Poppins)

## Project Structure

```
arshad-and-sons-webpage/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process required.

## Deployment

This website can be easily deployed to Vercel or GitHub Pages. Both platforms support static HTML/CSS/JS websites.

### Option 1: Deploy to Vercel

#### Method A: Using Vercel CLI (Recommended)

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Navigate to your project directory**:
   ```bash
   cd /path/to/arshad-and-sons-webpage
   ```

4. **Deploy**:
   ```bash
   vercel
   ```

5. Follow the prompts:
   - Set up and deploy? **Yes**
   - Which scope? (Select your account)
   - Link to existing project? **No**
   - Project name? (Press Enter for default or enter custom name)
   - Directory? (Press Enter for `./`)
   - Override settings? **No**

6. Your website will be deployed and you'll get a URL like `https://your-project-name.vercel.app`

#### Method B: Using Vercel Dashboard

1. Go to [vercel.com](https://vercel.com) and sign up/login
2. Click "Add New Project"
3. Import your Git repository (GitHub, GitLab, or Bitbucket)
   - If not using Git, you can drag and drop your project folder
4. Vercel will automatically detect it's a static site
5. Click "Deploy"
6. Your site will be live in seconds!

### Option 2: Deploy to GitHub Pages

#### Method A: Using GitHub Actions (Recommended)

1. **Create a GitHub repository**:
   - Go to GitHub and create a new repository
   - Name it `arshad-and-sons-webpage` (or any name you prefer)

2. **Push your code to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/arshad-and-sons-webpage.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose branch: `main`
   - Choose folder: `/ (root)`
   - Click "Save"

4. **Your site will be live at**:
   `https://YOUR_USERNAME.github.io/arshad-and-sons-webpage/`

#### Method B: Using gh-pages Branch

1. **Install gh-pages package**:
   ```bash
   npm install --save-dev gh-pages
   ```

2. **Add deploy script to package.json** (create one if it doesn't exist):
   ```json
   {
     "name": "arshad-and-sons-webpage",
     "version": "1.0.0",
     "scripts": {
       "deploy": "gh-pages -d ."
     },
     "devDependencies": {
       "gh-pages": "^6.0.0"
     }
   }
   ```

3. **Deploy**:
   ```bash
   npm run deploy
   ```

## Custom Domain Setup

### For Vercel:
1. Go to your project settings on Vercel
2. Click "Domains"
3. Add your custom domain
4. Follow the DNS configuration instructions

### For GitHub Pages:
1. Go to repository Settings > Pages
2. Enter your custom domain
3. Configure DNS records as instructed
4. GitHub will provide the required DNS settings

## Updating Content

To update the website content:

1. **Company Information**: Edit `index.html` and search for the relevant sections
2. **Styling**: Modify `styles.css` to change colors, fonts, or layout
3. **Functionality**: Update `script.js` for any interactive features

### Quick Updates:

- **Change Colors**: Edit CSS variables in `styles.css` (lines 3-11)
- **Update Contact Info**: Search for contact details in `index.html`
- **Modify Banking Details**: Find the banking section in `index.html`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

- The website is optimized for fast loading
- All external resources (fonts, icons) are loaded from CDNs
- Images should be optimized before adding (if you add images later)
- Consider using a service like TinyPNG for image optimization

## SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for description and keywords
- Proper heading hierarchy
- Alt text ready for images (when added)

## Support

For any issues or questions:
- Email: Arshedsons@gmail.com
- Phone: 0301-8664580

## License

© 2025 ARSHED & SONS ENTERPRISES. All rights reserved.

---

**Built with ❤️ for ARSHED & SONS ENTERPRISES**

