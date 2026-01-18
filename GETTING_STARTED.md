# Getting Started with Your New iA Writer Templates

## What You've Just Received

I've created two professional iA Writer templates tailored to your needs:

### 1. **Academic Paper Template** 📄
Based on your Ramanujan Nested Radicals paper, this template features:
- **STIX Two Text font** - The same professional serif used in academic mathematics papers
- **Elegant academic styling** - Justified text, proper margins, professional hierarchy
- **Mathematical support** - Excellent rendering of mathematical symbols and notation
- **Print-optimized** - Perfect for creating PDFs and printing

### 2. **Gaurav Tiwari Website Template** 🌐
Inspired by gauravtiwari.org, this template offers:
- **Inter font** - Modern, clean, web-native typography
- **Contemporary design** - Minimalist aesthetic with red accent color
- **Blog/article style** - Perfect for web content and portfolio pieces
- **Responsive layout** - Works beautifully on all devices

---

## Installation Instructions

### macOS
```bash
# Copy both templates to iA Writer's template directory
cp -r AcademicPaper.iatemplate ~/Library/Application\ Support/iA\ Writer/Templates/
cp -r GauravTiwari.iatemplate ~/Library/Application\ Support/iA\ Writer/Templates/

# Restart iA Writer
# Templates will appear in the template selection menu
```

### Windows
1. Locate your iA Writer installation folder
2. Copy `AcademicPaper.iatemplate` and `GauravTiwari.iatemplate` to the `Templates` folder
3. Restart iA Writer

### iOS/iPad
- If using iCloud sync with macOS, templates will sync automatically
- Otherwise, import through iA Writer's template manager

---

## Using Your Templates

### In iA Writer:
1. Create a new document
2. Select "Templates" from the menu
3. Choose either **Academic Paper** or **Gaurav Tiwari**
4. Start writing!

### Template Structure:
Each template includes:
- **Title Page** - For your document title and metadata
- **Document** - Main content area
- **Header** - Repeating header on each page
- **Footer** - Repeating footer with page info

---

## Template Features Comparison

| Feature | Academic | Website |
|---------|----------|---------|
| **Font** | STIX Two Text | Inter |
| **Font Type** | Serif | Sans-serif |
| **Best For** | Academic papers | Blog posts |
| **Accent Color** | None (neutral) | Red (#e74c3c) |
| **Text Style** | Justified | Left-aligned |
| **Max Width** | 8.5" (letter) | 900px |
| **Line Height** | 1.8 | 1.7 |
| **Math Support** | Excellent | Good |

---

## Customization Guide

### Changing Colors
Edit the CSS variables at the top of `style.css`:

**Academic Template:**
```css
:root {
	--body-color: #1a1a1a;        /* Text color */
	--border-color: #d0d0d0;      /* Borders */
	--light-bg: #fafafa;          /* Light background */
}
```

**Website Template:**
```css
:root {
	--primary-color: #2c3e50;     /* Main color */
	--accent-color: #e74c3c;      /* Red accent */
	--text-color: #333333;        /* Text */
}
```

### Changing Fonts
1. Go to Google Fonts (fonts.google.com)
2. Find a font you like
3. Copy the font import URL
4. Replace the `<link>` tag in the HTML files

**Example:**
```html
<!-- Original -->
<link href="https://fonts.googleapis.com/css2?family=STIX+Two+Text&display=swap" rel="stylesheet">

<!-- New font -->
<link href="https://fonts.googleapis.com/css2?family=Your+New+Font&display=swap" rel="stylesheet">
```

### Adjusting Spacing
Modify margins, padding, and line-height:

```css
body {
	margin: 0;                    /* Overall margin */
	padding: 1in;                 /* Inside spacing */
	line-height: 1.8;             /* Space between lines */
}
```

---

## File Structure

Each template is organized as:
```
TemplateName.iatemplate/
├── Contents/
│   ├── Info.plist              ← Metadata
│   └── Resources/
│       ├── document.html       ← Main content
│       ├── title.html          ← Title page
│       ├── header.html         ← Header
│       ├── footer.html         ← Footer
│       └── style.css           ← Styling
```

---

## Tips for Best Results

### For Academic Papers:
✓ Use the title page for paper metadata
✓ Academic blockquotes render beautifully
✓ Mathematical symbols display perfectly
✓ Exports to PDF maintain professional formatting
✓ Print output is optimized for double-sided printing

### For Website/Blog Content:
✓ The red accent helps highlight important points
✓ Tables look modern with hover effects
✓ Code blocks are styled for readability
✓ Title page gradient makes a great intro
✓ Responsive design works on phones/tablets

---

## Sample Content

Check out the included sample files:
- `SAMPLE_ACADEMIC.md` - Example content for Academic template
- `SAMPLE_WEBSITE.md` - Example content for Website template

Copy-paste these into your documents to see how they render!

---

## Documentation Files

- **INDEX.md** - Quick overview and navigation
- **README.md** - Complete feature documentation
- **INSTALLATION_GUIDE.md** - Detailed setup instructions
- **TEMPLATE_COMPARISON.md** - Side-by-side feature table
- **SAMPLE_ACADEMIC.md** - Academic template sample
- **SAMPLE_WEBSITE.md** - Website template sample

---

## Font Information

### STIX Two Text (Academic Template)
- Professional serif typeface
- Specifically designed for scientific and mathematical publishing
- Excellent support for mathematical symbols
- Free from Google Fonts
- Website: https://fonts.google.com/specimen/STIX+Two+Text

### Inter (Website Template)
- Modern, humanist sans-serif
- Designed for optimal screen readability
- System-friendly and web-native
- Free from Google Fonts
- Website: https://fonts.google.com/specimen/Inter

---

## Troubleshooting

**Templates not showing?**
- Ensure files are in the correct Templates folder
- Restart iA Writer
- Check file structure matches `.iatemplate/Contents/Resources/`

**Fonts not displaying?**
- Check internet connection (Google Fonts need to load)
- Verify font names match exactly in CSS
- Try with a system font temporarily

**Styles not working?**
- Clear iA Writer cache/preferences
- Check CSS syntax for typos
- Ensure style.css is linked in HTML files

---

## Resources

- **iA Writer:** https://ia.net/writer
- **Original Templates:** https://github.com/iainc/iA-Writer-Templates
- **STIX Two Font:** https://fonts.google.com/specimen/STIX+Two+Text
- **Inter Font:** https://fonts.google.com/specimen/Inter
- **Your Website:** https://gauravtiwari.org

---

## Next Steps

1. ✅ Install the templates (see Installation section above)
2. ✅ Create a new document and select a template
3. ✅ Try writing some content
4. ✅ Customize colors/fonts to your preference
5. ✅ Export to PDF or print

---

Enjoy your new templates! They're designed to make your writing look as great as the content itself.

**Questions?** Refer to the other documentation files or modify the CSS and HTML to suit your needs perfectly.
