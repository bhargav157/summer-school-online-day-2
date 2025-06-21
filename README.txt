# Personal Profile Card – CSS Summary

This file explains the use of different CSS types and selectors used in the assignment:

1. CSS Types Used:
   - Inline CSS: Applied to the main profile card using the `style` attribute to set the background color.
   - Internal CSS: Defined in a <style> block in the <head> to style <h1>, <h2>, and .contact p.
   - External CSS: Most styles are applied via the external file `style.css`.

2. Selectors Used:
   - Element selectors: `p`, `ul`, `a`, etc.
   - ID selector: `#profile-pic` for the image.
   - Class selector: `.bio` for the biography paragraph.
   - Group selector: `h1, h2` to apply styles to both headings.
   - Descendant selector: `.contact a` for styling links inside the contact section.
   - Attribute selector: `a[href]` to style all anchor tags with href attributes.

Bonus:
- Hover effect on contact links is implemented using `a:hover`.
- The `.profile-card` class adds shadow and border radius for visual appeal.
