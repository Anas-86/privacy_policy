# Gisty Privacy Policy

A professional privacy policy website for the Gisty mobile app, hosted on GitHub Pages.

## Files Included

- `index.html` - Main privacy policy page
- `styles.css` - Responsive styling
- `README.md` - This file

## How to Host on GitHub Pages

Follow these steps to host this privacy policy on your GitHub account:

### Step 1: Create a New Repository

1. Go to [GitHub.com](https://github.com) and log in to your account
2. Click the **+** icon in the top-right corner and select **New repository**
3. Name your repository: `gisty-privacy-policy` (or any name you prefer)
4. Add a description: "Privacy Policy for Gisty app"
5. Choose **Public** (required for GitHub Pages)
6. Click **Create repository**

### Step 2: Upload Files to the Repository

**Option A: Using Git (Recommended)**

1. Open your terminal/command prompt
2. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/gisty-privacy-policy.git
   cd gisty-privacy-policy
   ```
3. Copy the files (`index.html`, `styles.css`) into this directory
4. Add and commit the files:
   ```bash
   git add .
   git commit -m "Add privacy policy"
   git push origin main
   ```

**Option B: Using GitHub Web Interface**

1. In your repository, click **Add file** → **Upload files**
2. Drag and drop `index.html` and `styles.css` into the upload area
3. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top-right of the repository page)
3. Scroll down to the **Pages** section (left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

### Step 4: Access Your Privacy Policy

GitHub will provide you with a URL like:
```
https://YOUR_USERNAME.github.io/gisty-privacy-policy/
```

Your privacy policy will be live at this URL within a few minutes.

## Customization

### Change the Date
Edit `index.html` and update the date in this line:
```html
<strong>Last updated:</strong> January 21, 2026
```

### Change Colors
Edit `styles.css` and modify the CSS variables at the top:
```css
:root {
    --primary-color: #1a73e8;  /* Change this color */
    --primary-dark: #1557b0;
    /* ... other colors ... */
}
```

### Update Contact Email
Edit `index.html` and change the email in the Contact section:
```html
<a href="mailto:your-email@example.com">your-email@example.com</a>
```

## Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Professional styling with Google-inspired design
- ✅ Fast loading and SEO-optimized
- ✅ Print-friendly
- ✅ Accessible and semantic HTML
- ✅ No external dependencies

## Browser Support

Works on all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This privacy policy template is provided as-is for use with your Gisty app.
