# Monogatari Mokuji - HTML + CSS + JS Template

## Overview
Monogatari Mokuji is a lightweight, responsive HTML + CSS + JavaScript template designed for reading novels, light novels, or story collections. It features a two-column desktop layout with a section for images/graphics and a content area, while adapting gracefully for mobile and tablet screens.

The template is ideal for building a book reader web app, online story showcase, or personal library site.

## Features

- Desktop Layout: Two-column design with an image section and a content section.
- Responsive Design: Automatically adjusts for mobile and tablet screens.
- Typography: Uses Spectral font for readability.
- Navigation: Links for chapters, volumes, and main pages.
- Interactive Elements: Back-to-top button, tooltips, and blockquote highlights.
- Lightweight JS: Minimal JavaScript using fetch to load templates for modularity.
- Blockquotes & Highlights: Styled for emphasis while keeping content readable.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/padiks/monogatari-mokuji-template.git
   ```

2. Open the HTML file in a browser:
   - Main file: index.html
   - Book index: books/lorem-ipsum/index.html
   - Volumes: books/lorem-ipsum/volume-1.html (content loaded via fetch)

3. Customization:
   - Modify content inside content.html, index-content.html, or volume-1-content.html.
   - Update assets/css/style.css for colors, fonts, and layout tweaks.
   - Replace images in assets/images/ with your own.
   - Replace book placeholders, titles, chapters, and summaries with your content.

## File Structure

```
monogatari-mokuji-template/
├── index.html                     # Main page
├── content.html                   # Main content template
├── assets/
│   ├── css/
│   │   └── style.css              # Main stylesheet
│   └── images/                    # Image assets
├── templates/
│   ├── footer.html                # Footer template
│   ├── images.html                # Image group template
│   └── images-dup.html            # Duplicate image template
├── books/
│   ├── lorem-ipsum/
│   │   ├── index.html             # Book index page
│   │   ├── index-content.html     # Book index content
│   │   ├── volume-1.html          # Volume page
│   │   └── volume-1-content.html  # Volume content
│   └── another-book/
│       └── ...                    # Additional books
├── README.md                      # Project overview
└── LICENSE                        # MIT License file
```


## License

This project is licensed under the MIT License for the modifications made by the author.

> Note:
> - Original templates are © CodeStitch and used under their license. Redistribution of unmodified templates is not allowed.
> - Images sourced from Pexels (https://www.pexels.com/) and icons from Flaticon (https://www.flaticon.com/) remain under their respective licenses and must be credited.

See LICENSE for details.

## Credits

- Created by padiks with guidance from ChatGPT.
- Templates: Modified from CodeStitch.
- Fonts: Spectral.
- Icons: Flaticon (Free License).
- Images: Pexels (Free for personal/commercial use).

## Notes

- Fully compatible with modern browsers.
- Designed for clean, readable, and content-focused layout.
- Modular template loading via fetch for better maintenance.

## Contributing

This template is provided as a finished resource. No additional contributions are expected at this time.

---

Enjoy your clean, responsive reading template for novels and story collections!
