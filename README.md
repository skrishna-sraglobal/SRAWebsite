# IAM Solutions Website

A professional website for Identity and Access Management (IAM) consulting services, showcasing expertise in SailPoint, Saviynt, and enterprise security solutions.

## Features

- Clean, professional design with responsive layout
- Detailed service offerings and platform expertise
- Contact section with service selection options
- Mobile-friendly navigation
- Modern CSS styling

## GitHub Pages Deployment Instructions

### Method 1: Using GitHub Web Interface

1. **Create a New Repository**
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon in the top right and select "New repository"
   - Name your repository (e.g., `iam-website`)
   - Choose "Public" visibility
   - Click "Create repository"

2. **Upload Files**
   - Click "uploading an existing file"
   - Drag and drop `index.html` and `styles.css` from this folder
   - Commit the files

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be published at: `https://yourusername.github.io/iam-website/`

### Method 2: Using Git Command Line

1. **Initialize Git Repository**
   ```bash
   cd iam-website
   git init
   git add .
   git commit -m "Initial commit: IAM Solutions website"
   ```

2. **Connect to GitHub**
   ```bash
   git remote add origin https://github.com/yourusername/iam-website.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Follow step 3 from Method 1 above

## Customization

Before deploying, update the following in `index.html`:

- Replace `solutions@yourcompany.com` with your actual email address
- Update `[Insert Location / Remote Headquarters]` with your office location
- Add actual links to the consultation and brochure buttons
- Update company name in the navigation and footer if needed

## File Structure

```
iam-website/
├── index.html          # Main website HTML
├── styles.css          # CSS styling
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This website template is provided as-is for your use.
