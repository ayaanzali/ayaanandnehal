# Valentine's Day Website - ayaanandnehal.com

A romantic, elegant single-page Valentine's Day website built with pure HTML, CSS, and JavaScript.

## Features

- **Landing Page**: Beautiful hero section with floating heart animations
- **Timeline Section**: 7 memory cards with alternating layout and smooth scroll animations
- **Interactive Games**: Love Calculator and Romantic Fortune teller
- **Finale Section**: Playful "Will You Be My Valentine?" with escaping "No" button
- **Easter Eggs**: Konami code secret message, clickable floating hearts
- **Fully Responsive**: Works perfectly on mobile, tablet, and desktop

## Deployment to GitHub Pages

1. **Create a GitHub repository** (if you haven't already)
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Valentine's Day website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

3. **Custom Domain Setup** (for ayaanandnehal.com)
   - In the same GitHub Pages settings, add your custom domain: `ayaanandnehal.com`
   - Update your DNS records:
     - Add a CNAME record pointing `ayaanandnehal.com` to `YOUR_USERNAME.github.io`
     - Or add A records pointing to GitHub's IP addresses:
       - 185.199.108.153
       - 185.199.109.153
       - 185.199.110.153
       - 185.199.111.153

## Customization

### Adding Your Photos

Replace the placeholder images in the timeline section:
1. Add your photos to the `/images` folder (already created)
2. Name your images as follows:
   - Memory 1: `memory1-1.jpg` and `memory1-2.jpg`
   - Memory 2: `memory2-1.jpg` and `memory2-2.jpg`
   - Memory 3: `memory3-1.jpg` and `memory3-2.jpg`
   - Memory 4: `memory4-1.jpg` and `memory4-2.jpg`
   - Memory 5: `memory5-1.jpg` and `memory5-2.jpg`
   - Memory 6: `memory6-1.jpg` and `memory6-2.jpg`
   - Memory 7: `memory7-1.jpg` and `memory7-2.jpg`

3. Each memory card displays two images side by side
4. Images should be in JPG format and will automatically resize to fit

### Updating Memory Content

Edit the memory cards in the timeline section:
- Update dates: Change `MM/DD/YYYY` to actual dates
- Update titles: Change memory titles
- Update descriptions: Replace placeholder text with your actual memories

### Color Customization

All colors are defined as CSS variables at the top of the `<style>` section. You can easily change:
- `--primary-pink`: Main pink color
- `--rose-gold`: Accent color
- And all other color variables

## File Structure

```
ayaanandnehal.com/
├── index.html          # Main website file (all-in-one)
├── README.md          # This file
└── images/            # (Optional) Add your photos here
    ├── memory-1.jpg
    ├── memory-2.jpg
    └── ...
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Single HTML file for fast loading
- No external dependencies (except Google Fonts)
- Optimized animations using CSS transforms
- Lazy loading ready (images can be lazy loaded if needed)

## License

Personal project - feel free to customize for your own use!

---

Made with 💕 for Nehal

