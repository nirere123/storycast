# Dream in Progress — Young Entrepreneur Stories

A three-page accessible storytelling microsite prototype for the Advanced Front-end Web Development assignment. The concept shares early-stage journeys of young entrepreneurs through editorial story cards, a detail page, and an About / Access page.

## Pages
- `index.html` — home and story library
- `story/amina.html` — sample story detail page with a written transcript
- `about.html` — mission and accessibility information

## Technology
- Semantic HTML5
- Sass (`sass/main.scss`) with partials for colors, typography, and spacing
- Compiled CSS (`css/style.css`)
- CSS Grid, Flexbox, media queries, and a container query
- No CSS or JavaScript framework

## Run locally
1. Download or clone this repository.
2. Open the folder in VS Code.
3. Open `index.html` in a browser, or use the Live Server extension.
4. If you edit Sass, install Sass and compile from the project root:

```bash
sass sass/main.scss css/style.css --watch
```

## Accessibility checklist
- [x] Semantic landmarks and heading hierarchy
- [x] Skip link to main content
- [x] Visible keyboard focus states
- [x] Descriptive alt text for informative images
- [x] Written transcript for the sample interview
- [x] Responsive layout for desktop, tablet, and mobile
- [x] Reduced-motion preference supported
- [x] Container query used for the media panel
- [ ] Test all final color combinations with a WCAG contrast checker
- [ ] Test every page with keyboard-only navigation and a screen reader
- [ ] Add captions (`<track kind="captions">`) if real video is added
- [ ] Replace fictional sample content with researched/consented stories if required

## Important content note
Amina and the interview transcript are fictional examples made for the prototype. Do not present them as a real interview. Replace sample content with a real interview only after obtaining permission, or keep the fictional content clearly labelled.

## Project structure
```text
dream-in-progress/
├── index.html
├── about.html
├── story/
│   └── amina.html
├── sass/
│   ├── _colors.scss
│   ├── _typography.scss
│   ├── _spacing.scss
│   └── main.scss
├── css/
│   └── style.css
├── docs/
│   ├── research-document.pdf
│   └── sitemap.md
└── README.md
```

## Design rationale
The cream background, dark green typography, and lime accents create a warm, editorial identity. Large headings and story photography help visitors scan the content. The story detail page prioritizes readable text and a transcript rather than relying on media alone.

## figma link
https://www.figma.com/design/nE6KJ6mURLlW4a2NmgE9bu/storycast--website--mockups?node-id=0-1&t=0y185Mazak3hFVGW-1
