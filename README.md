Debugging Notes

HTML Fixes:

Missing lang attribute: Added lang="en" to the <html> tag for accessibility and standards compliance.

Empty <meta> tag: Added charset="UTF-8" and completed the viewport line with: <meta name="viewport" content="width=device-width, initial-scale=1.0">

Trailing slashes on <link> tags: Removed self-closing slashes (/) for HTML5 compliance.

Missing alt attribute on image: Added alt="Easter Bunny Profile Image" to <img> tag for accessibility.

Improper nesting of tags: Moved paragraph content out of <h3> tag and placed it in a proper <p> tag.

Stray character in header: Removed an extra < symbol that appeared after a paragraph inside the header.

Missing closing tags: Added </body> and </html> at the bottom of the page to close the document properly.

Header cleanup: Wrapped <h1> in a <div class="header-content"> for better structure and styling.

CSS Fixes:

Line 8 – Background color: Changed background color to white.

Line 24 – Removed rule: Deleted an unused or unnecessary rule.

Line 33 – Sidebar/menu update: Removed "menu" and added JavaScript functionality; styles for sidebar were added to style.css.

Line 43 – Font size fix: Fixed font-size: 5 vw to font-size: 5vw (removed space).

Line 60 – Clean layout: Removed <br> tags to avoid unnecessary spacing.

Line 66 – Line height typo: Corrected line-height: 1.35me to line-height: 1.35em.

Line 85 – Invalid color: Fixed hex color #FE27122 by removing the extra digits; corrected to #FE2712 (red).

Line 94 – Invalid text-decoration: Replaced text-decoration: all with text-decoration: none.

Heading colors and size:

Changed <h4> and <h5> text colors.

Adjusted font size for <h5> to improve visibility.