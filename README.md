# iA Writer Templates - Custom Collection

This repository contains two custom templates for iA Writer, created with elegant typography and modern design principles.

## Templates

### 1. Academic Paper Template

An elegant template for academic papers and professional mathematical documents, styled after your paper on Ramanujan Nested Radicals.

**Features:**
- **Font**: STIX Two Text from Google Fonts (professional serif typeface ideal for academic content)
- **Styling**: Elegant academic paper layout with justified text, proper margins (1-inch defaults), and professional spacing
- **Typography**: 
  - Body text: 11pt STIX Two Text
  - Line height: 1.8 for comfortable reading
  - Headings: Hierarchical sizes from 24pt (H1) to 10pt (H6)
- **Design Elements**:
  - Clean borders under major headings (H2)
  - Academic blockquote styling with italics
  - Professional table formatting with alternating row colors
  - Code blocks with subtle background
  - Proper print optimization with widow/orphan control
- **Layout Options**: Includes separate title page, header, footer, and document sections
- **Best for**: Mathematical papers, academic articles, research documents, technical writing

### 2. Gaurav Tiwari Website Template

A modern, minimalist template inspired by gauravtiwari.org with contemporary web design principles.

**Features:**
- **Fonts**: 
  - Primary: Inter (modern sans-serif)
  - Code: Inconsolata (monospace for code blocks)
- **Styling**: Clean, modern web-inspired layout with generous whitespace and contemporary typography
- **Typography**:
  - Body text: 1rem Inter with 1.7 line height
  - Headings: Hierarchical sizes with bold accent red left borders on H2
  - Comfortable reading with optimal line length (~900px max-width)
- **Design Elements**:
  - Accent color: #e74c3c (red) for emphasis
  - Red left borders on H2 headings for visual hierarchy
  - Background gradient on title page
  - Subtle borders and light backgrounds for code blocks
  - Hover effects on links and table rows
  - Modern blockquote styling with accent borders
- **Responsive**: Includes mobile-friendly media queries
- **Best for**: Blog posts, articles, web content, portfolio pieces, documentation, personal writing

## File Structure

Each template follows the standard iA Writer template structure:

```
TemplateName.iatemplate/
├── Contents/
│   ├── Info.plist (metadata and configuration)
│   └── Resources/
│       ├── document.html (main content page)
│       ├── title.html (title page)
│       ├── header.html (header section)
│       ├── footer.html (footer section)
│       └── style.css (styles)
```

## Installation

1. Copy the `.iatemplate` folders to your iA Writer templates directory:
   - **macOS**: `~/Library/Application Support/iA Writer/Templates/`
   - **iOS**: The app handles this through the template manager
   - **Windows**: Check your iA Writer installation directory

2. Restart iA Writer

3. The templates will appear in the template selection menu

## Customization

Both templates are easy to customize:

- **Colors**: Edit the CSS variable definitions in `style.css`
- **Fonts**: Modify the Google Fonts import URLs in the HTML files
- **Spacing**: Adjust margins, padding, and line-height values
- **Print styles**: Modify the `@media print` section for different print output

## Font Notes

- **STIX Two Text**: Best viewed with the font downloaded from Google Fonts. It provides proper mathematical symbol support for academic papers.
- **Inter**: Modern system-friendly font that works across all devices and platforms.

## License

These templates are provided as-is for personal use. Feel free to modify and customize as needed.

## Author

Created by Gaurav Tiwari - https://gauravtiwari.org

---

For more information about iA Writer templates, visit: https://github.com/iainc/iA-Writer-Templates