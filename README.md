# QR Generator Pro

A modern web application for generating QR codes with labels and exporting them to PDF. This application runs entirely in the browser with no backend required.

## Features

- ✨ Generate multiple QR codes at once
- 🏷️ Add custom labels to each QR code
- 📄 Export all codes to a single PDF
- 🎨 Modern, responsive UI with dark theme
- 📱 Works on desktop and mobile
- 🔒 Privacy-focused: all processing happens in your browser
- ⚡ Fast and lightweight

## Demo

Visit the live demo at: `https://[your-username].github.io/[repository-name]/`

## Deployment to GitHub Pages

### Method 1: Quick Setup

1. Create a new repository on GitHub
2. Upload the `index.html` file to the repository
3. Go to repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select the `main` branch and `/ (root)` folder
6. Click "Save"
7. Your site will be available at `https://[your-username].github.io/[repository-name]/`

### Method 2: Using Git CLI

```bash
# Clone or create a new repository
git init qr-generator-pro
cd qr-generator-pro

# Copy the index.html file to this directory

# Commit and push
git add index.html README.md
git commit -m "Initial commit: QR Generator Pro"
git branch -M main
git remote add origin https://github.com/[your-username]/[repository-name].git
git push -u origin main

# Enable GitHub Pages
# Go to repository Settings → Pages → Select main branch → Save
```

## Usage

1. **Enter Codes**: Type or paste your codes into the textarea, one per line
   - Example: `A-00-B-01`, `A-00-B-02`, etc.

2. **Choose Orientation**: Select landscape or portrait for the PDF pages

3. **Set Filename**: Enter a custom filename for your PDF (optional)

4. **Generate**: Click "Generate QR Codes" to create the QR codes and download the PDF

## Technical Details

- **Pure HTML/CSS/JavaScript**: No build process required
- **Libraries Used**:
  - QRCode.js: QR code generation
  - jsPDF: PDF creation
- **Browser Compatibility**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)

## Customization

You can customize the application by editing the `index.html` file:

- **Colors**: Modify the CSS variables in the `:root` selector
- **Fonts**: Change the Google Fonts imports and font-family declarations
- **QR Code Size**: Adjust the `qrSize` variable in the PDF generation function
- **Page Margins**: Modify the `margin` variable in the PDF generation function

## Privacy & Security

This application:
- Runs entirely in your browser
- Does not send any data to external servers
- Does not store or track your information
- All QR code generation happens client-side

## License

This project is open source and available for personal and commercial use.

## Support

If you encounter any issues or have suggestions:
1. Open an issue on GitHub
2. Provide details about your browser and the problem
3. Include any error messages from the browser console

## Comparison to Original Python Application

This web version provides the same core functionality as the original Python desktop application:

| Feature | Python Version | Web Version |
|---------|---------------|-------------|
| QR Code Generation | ✅ | ✅ |
| Custom Labels | ✅ | ✅ |
| PDF Export | ✅ | ✅ |
| Portrait/Landscape | ✅ | ✅ |
| Batch Processing | ✅ | ✅ |
| Installation Required | ❌ Requires Python | ✅ None |
| Cross-Platform | ✅ | ✅ |
| Offline Use | ✅ | ✅ (after first load) |

## Credits

Converted from a Python desktop application to a modern web application for easier accessibility and use.
