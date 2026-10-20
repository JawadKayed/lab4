# CCT360 Creative Hub

A responsive, single-page directory for creative workshops. The site uses semantic HTML5 and plain CSS; it has no framework, build step, or remote image dependency.

## View the site

Live website: [CCT360 Creative Hub](https://jawadkayed.github.io/lab4/).

GitHub repository: [JawadKayed/lab4](https://github.com/JawadKayed/lab4).

To view it locally, open `index.html` in a browser. The workshop artwork is stored locally in `assets/` and the stylesheet is `css/style.css`.

## Layout and rubric notes

- CSS Grid handles the hero/sidebar proportions and the workshop gallery. Both are single-column by default and gain their desktop columns only at `min-width: 768px`.
- Flexbox handles the header and footer layout, and each workshop card uses a vertical flex direction. `margin-top: auto` on the card action aligns buttons when descriptions vary; grid item stretching keeps cards in a row equal in height.
- The shared content width is capped at 1280px, with 20px minimum side gutters. This yields 80px margins at a 1440px viewport.
- All images are local SVG placeholders with relative `assets/` paths. Navigation and card actions point to existing sections on this page.

## Design tokens

| Token | Value | Use |
| --- | --- | --- |
| Primary | `#245C4F` | Brand, links, and primary actions |
| Secondary | `#F1C879` | Highlights and supporting accents |
| Page background | `#F8F6EF` | Light cream canvas |
| Main text | `#202824` | Body and heading text |
| Typography | Arial, Helvetica, sans-serif | All text |
| Body | `16px` | Paragraphs and supporting text |
| H1 | `32px` mobile / `48px` desktop | Main spotlight heading |
| H2 | `26px` mobile / `32px` desktop | Section headings |
| H3 | `24px` | Workshop headings |
| Spacing | `24px` | Shared section and grid gap |

## Figma wireframes

[Open the CCT360 Creative Hub Figma design](https://www.figma.com/design/2z37TCWL15WpBU33RGT4Al/Untitled?node-id=0-1&t=geaehPktHexbs3Yz-1), containing desktop and mobile wireframes and design tokens.