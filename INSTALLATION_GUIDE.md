# Installation and Usage Guide

## Quick Start

### Installation

1. **macOS:**
   ```bash
   cp -r AcademicPaper.iatemplate ~/Library/Application\ Support/iA\ Writer/Templates/
   cp -r GauravTiwari.iatemplate ~/Library/Application\ Support/iA\ Writer/Templates/
   ```

2. **Windows:**
   - Copy the `.iatemplate` folders to your iA Writer templates directory
   - Default location: `%APPDATA%\iA Writer\Templates\`

3. **iOS/iPad:**
   - Templates sync automatically if using iCloud
   - Or manually import through the template manager

4. **Restart iA Writer** - The new templates should now appear in your template selection menu

## Template Descriptions

### Academic Paper Template

**Best for:** Academic papers, mathematical articles, research documents, technical writing

**Key Characteristics:**
- STIX Two Text font for professional academic appearance
- 11pt base font size with 1.8 line height
- Justified text alignment
- 1-inch margins (standard academic format)
- Professional heading hierarchy
- Excellent mathematical symbol support

**Customization:**
- Modify fonts in `document.html`, `title.html`, `header.html`, `footer.html`
- Change colors in the CSS variables section (`:root`)
- Adjust margins in `body[data-document]` CSS rule

### Gaurav Tiwari Website Template

**Best for:** Blog posts, articles, web content, portfolio pieces, documentation

**Key Characteristics:**
- Inter font for modern, clean appearance
- 1rem base font size with 1.7 line height
- Contemporary design with accent red (#e74c3c)
- Maximum width of 900px for optimal reading
- Red accent borders on major headings
- Responsive design for various screen sizes

**Customization:**
- Color scheme in CSS variables (`:root`)
- Font family in the Google Fonts import line
- Spacing in margin/padding properties
- Accent color throughout the stylesheet

## Using the Templates

### In iA Writer:

1. Open iA Writer
2. Create a new document
3. Select your desired template from the template menu
4. Start writing!

### Template Parts:

- **Title Page:** Use for document/article title and metadata
- **Document:** Main content area
- **Header:** Repeating header on each page
- **Footer:** Repeating footer with page numbers, etc.

## Customization Tips

### Changing Colors

Edit the CSS variables in `style.css`:

```css
:root {
	--primary-color: #2c3e50;
	--accent-color: #e74c3c;
	--text-color: #333333;
	/* ... modify as needed ... */
}
```

### Changing Fonts

Modify the Google Fonts import URLs in the HTML files, or replace with local fonts:

```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT:wght@400;700&display=swap" rel="stylesheet">
```

Then update the font-family in CSS.

### Adjusting Spacing

Modify these key CSS properties:

- `margin` - Space around elements
- `padding` - Space inside elements
- `line-height` - Space between lines of text
- `letter-spacing` - Space between letters

## Print Optimization

Both templates include print-optimized styles in the `@media print` section:

- Removes unnecessary backgrounds and borders
- Prevents page breaks in the middle of content
- Optimizes heading widows and orphans
- Simplifies links and emphasis

## Troubleshooting

**Templates not showing in iA Writer:**
- Ensure the folder structure is correct (`.iatemplate/Contents/Resources/`)
- Check that all required files exist (Info.plist, document.html, style.css)
- Restart iA Writer

**Fonts not displaying correctly:**
- Ensure internet connection for Google Fonts
- Check that font names match exactly in CSS
- Test with a system font as fallback

**Styling not applied:**
- Clear iA Writer cache (app preferences)
- Verify CSS syntax is correct
- Check that style.css is linked in HTML files

## Support

For issues with iA Writer templates in general, visit:
- https://github.com/iainc/iA-Writer-Templates
- https://ia.net/writer

For customization help, review the CSS comments in each template's style.css file.
