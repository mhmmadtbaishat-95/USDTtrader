# Netlify Deployment Guide

## Quick Deploy to Netlify

### Option 1: Drag & Drop (Easiest)
1. Go to [netlify.com](https://netlify.com)
2. Sign up/Login with your account
3. Drag and drop the entire `USDT-Trader` folder onto the Netlify dashboard
4. Your site will be live in seconds!

### Option 2: GitHub Integration (Recommended)
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to [netlify.com](https://netlify.com)
4. Click "New site from Git"
5. Connect your GitHub account
6. Select your repository
7. Deploy settings are already configured in `netlify.toml`
8. Click "Deploy site"

### Option 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy from current directory
netlify deploy

# For production deployment
netlify deploy --prod
```

## Post-Deployment

### Custom Domain (Optional)
1. In Netlify dashboard, go to "Domain settings"
2. Add your custom domain
3. Configure DNS settings as instructed

### Environment Variables (Not needed for this project)
This is a static site with no server-side requirements.

### Performance Optimization
The site is already optimized with:
- Minified CSS and JavaScript
- Optimized images
- Proper caching headers
- Mobile-first responsive design

## Mobile Usage

Once deployed, you can:
1. Bookmark the site on your mobile device
2. Add to home screen for app-like experience
3. Use offline (data persists in local storage)
4. Access from any device with the same URL

## Data Backup

Your trading data is stored locally in your browser. To backup:
1. Use the CSV export feature regularly
2. Save the exported files to cloud storage
3. Data will persist across sessions on the same device

## Updates

To update the site:
1. Make changes to your local files
2. Push to GitHub (if using Git)
3. Netlify will automatically redeploy
4. Or drag & drop updated files to Netlify dashboard

---

**Your USDT Trading Portal is ready for deployment! 🚀**
